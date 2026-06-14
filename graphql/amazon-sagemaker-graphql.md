# Amazon SageMaker GraphQL Schema

## Overview

This GraphQL schema provides a conceptual graph representation of the [Amazon SageMaker REST API](https://docs.aws.amazon.com/sagemaker/latest/APIReference/). SageMaker is a fully managed ML platform for building, training, and deploying machine learning models at scale on AWS. The schema normalises SageMaker's deeply nested JSON request/response shapes into well-typed GraphQL objects, making it straightforward to explore the surface area of the API, generate documentation, or bootstrap a GraphQL gateway on top of the underlying REST endpoints.

## Schema File

`amazon-sagemaker-schema.graphql`

## Type Coverage

The schema defines the following named type groups:

### Training

| Type | Description |
|------|-------------|
| `TrainingJob` | Full representation of a SageMaker training job including status, metrics, and configuration |
| `TrainingJobStatus` | Enum — InProgress, Completed, Failed, Stopping, Stopped |
| `TrainingInput` | Input channel configuration for a training job |
| `AlgorithmSpec` | Algorithm image, input mode, and metric definitions |
| `MetricDefinition` | Name/regex pair used to extract a metric from training logs |
| `OutputDataConfig` | S3 path and KMS key for training output artifacts |
| `ResourceConfig` | Instance type, count, and storage for the training cluster |
| `StoppingCondition` | Maximum runtime and wait time bounds |
| `CheckpointConfig` | S3 URI and local path for training checkpoints |
| `DebuggingConfig` | Debug hook, rule configurations, and TensorBoard output |
| `VpcConfig` | Security groups and subnets for network-isolated training |

### Model

| Type | Description |
|------|-------------|
| `Model` | A deployable SageMaker model with one or more containers |
| `ModelArtifact` | S3 URI of a trained model artifact |
| `Container` | Docker container definition including image, environment, and mode |
| `ContainerMode` | Enum — SingleModel or MultiModel |
| `ModelInput` | Data input configuration for a model container |
| `InferenceExecutionConfig` | Controls single-model vs multi-model inference execution |

### Model Package / Registry

| Type | Description |
|------|-------------|
| `ModelPackage` | Versioned, shareable model artifact with inference specification |
| `ModelPackageGroup` | Logical grouping of versioned model packages |
| `ModelPackageStatus` | Enum — Pending, InProgress, Completed, Failed, Deleting |
| `InferenceSpecification` | Containers and supported instance types for inference |
| `SourceAlgorithmSpecification` | Originating algorithm and model data for a model package |
| `ModelMetrics` | Quality, data-quality, bias, and explainability metric sources |

### Algorithm

| Type | Description |
|------|-------------|
| `Algorithm` | A publishable SageMaker algorithm with training and inference specs |
| `TrainingChannelSpec` | Named channel definition within an algorithm's training spec |
| `HyperParameterSpecification` | Hyper-parameter metadata including type, range, and tunability |

### Endpoint

| Type | Description |
|------|-------------|
| `EndpointConfig` | Configuration for a hosted endpoint including production variants |
| `EndpointVariant` | A single model variant within an endpoint configuration |
| `CaptureConfig` | Data capture settings for model monitoring |
| `Endpoint` | A live hosted model endpoint |
| `EndpointStatus` | Enum — OutOfService, Creating, Updating, InService, Deleting, Failed, etc. |
| `EndpointSummary` | Lightweight summary returned by list operations |

### Transform Job

| Type | Description |
|------|-------------|
| `TransformJob` | Batch transform job for offline inference over S3 data |
| `TransformInput` | S3 data source and split type for transform input |
| `TransformOutput` | S3 path and assembly settings for transform output |
| `TransformResource` | Instance type and count for the transform cluster |

### Compilation (Neo)

| Type | Description |
|------|-------------|
| `CompilationJob` | Neo compilation job to optimise a model for a target device |
| `CompilationJobStatus` | Enum — INPROGRESS, COMPLETED, FAILED, STARTING, STOPPING, STOPPED |
| `InputConfig` | S3 URI, framework, and data input config for compilation |
| `NeoOutputConfig` | S3 output location and target device/platform for compiled model |

### Hyperparameter Tuning

| Type | Description |
|------|-------------|
| `HyperParameterTuning` | Automated hyperparameter optimisation job |
| `HyperParameterRange` | Integer, continuous, and categorical parameter ranges for search |
| `BestTrainingJob` | The best-performing training job identified by tuning |

### Pipeline

| Type | Description |
|------|-------------|
| `Pipeline` | A SageMaker ML pipeline definition |
| `PipelineStep` | A single step within a pipeline definition |
| `PipelineExecution` | A single run of a pipeline |
| `StepExecution` | Execution status and metadata for an individual pipeline step |
| `PipelineStatus` | Enum — Active, Deleting |
| `PipelineExecutionStatus` | Enum — Executing, Stopping, Stopped, Failed, Succeeded |
| `StepStatus` | Enum — Starting, Executing, Stopping, Stopped, Failed, Succeeded, Cached, Skipped |

### Feature Store

| Type | Description |
|------|-------------|
| `FeatureGroup` | A SageMaker Feature Store feature group |
| `FeatureDefinition` | A named feature with type within a feature group |
| `FeatureType` | Enum — Integral, Fractional, String |
| `Record` | A feature store record containing feature values |
| `OnlineStoreConfig` | Settings for the low-latency online feature store |
| `OfflineStoreConfig` | S3-backed offline feature store configuration |

### Experiments and Trials

| Type | Description |
|------|-------------|
| `Experiment` | A SageMaker experiment for grouping related trials |
| `Trial` | A single trial within an experiment |
| `TrialComponent` | An atomic unit of work tracked within a trial |

### Lineage

| Type | Description |
|------|-------------|
| `LineageEntity` | A node in the ML lineage graph |
| `Action` | A lineage action representing a step taken |
| `Context` | A lineage context grouping related entities |
| `Artifact` | A lineage artifact such as a dataset or model |
| `Association` | A directed edge between two lineage entities |

### Processing

| Type | Description |
|------|-------------|
| `ProcessingJob` | A data processing or model evaluation job |
| `ProcessingInput` | S3 or dataset-definition input for a processing job |
| `ProcessingOutput` | S3 or Feature Store output from a processing job |
| `ProcessingResource` | Cluster configuration for a processing job |

### Monitoring

| Type | Description |
|------|-------------|
| `MonitoringSchedule` | Scheduled monitoring job for a deployed endpoint |
| `DataQualityMonitor` | Monitors statistical properties and data drift |
| `ModelQualityMonitor` | Monitors model quality against ground truth |
| `MonitoringScheduleStatus` | Enum — Pending, Failed, Scheduled, Stopped |

### Inference Experiment

| Type | Description |
|------|-------------|
| `InferenceExperiment` | A/B or shadow mode experiment on a live endpoint |
| `InferenceExperimentStatus` | Enum — Creating, Created, Updating, Running, Starting, Stopping, Completed, Cancelled |
| `ShadowModeConfig` | Shadow model variant sampling configuration |

### Project, Space, Domain, User

| Type | Description |
|------|-------------|
| `Project` | A SageMaker project backed by Service Catalog |
| `Space` | A private collaborative workspace within a SageMaker Domain |
| `Domain` | An isolated SageMaker environment for a team |
| `UserProfile` | A user within a SageMaker Domain |

## Queries

The `Query` type exposes read operations across all resource categories:

- `trainingJob(trainingJobName)` / `listTrainingJobs(...)`
- `model(modelName)` / `listModels(...)`
- `modelPackage(modelPackageName)` / `modelPackageGroup(...)` / `listModelPackages(...)`
- `endpointConfig(endpointConfigName)` / `endpoint(endpointName)` / `listEndpoints(...)`
- `transformJob(transformJobName)` / `listTransformJobs(...)`
- `compilationJob(compilationJobName)` / `listCompilationJobs(...)`
- `hyperParameterTuningJob(...)` / `listHyperParameterTuningJobs(...)`
- `pipeline(pipelineName)` / `pipelineExecution(...)` / `listPipelines(...)` / `listPipelineExecutions(...)` / `listPipelineExecutionSteps(...)`
- `featureGroup(featureGroupName)` / `listFeatureGroups(...)`
- `experiment(experimentName)` / `trial(trialName)` / `trialComponent(trialComponentName)` / `listExperiments(...)` / `listTrials(...)`
- `listArtifacts(...)` / `listActions(...)` / `listContexts(...)` / `listAssociations(...)` / `queryLineage(...)`
- `processingJob(processingJobName)` / `listProcessingJobs(...)`
- `monitoringSchedule(monitoringScheduleName)` / `listMonitoringSchedules(...)`
- `inferenceExperiment(name)` / `listInferenceExperiments(...)`
- `project(projectName)` / `listProjects(...)`
- `domain(domainId)` / `space(domainId, spaceName)` / `userProfile(domainId, userProfileName)` / `listDomains(...)` / `listSpaces(...)` / `listUserProfiles(...)`

## Mutations

The `Mutation` type exposes create, update, delete, and lifecycle operations for all resource categories including tag management via `addTags`, `deleteTags`, and `listTags`.

## Source

- API Reference: https://docs.aws.amazon.com/sagemaker/latest/APIReference/
- Schema source: Conceptual — derived by hand from the SageMaker REST API reference documentation
- Provider: Amazon Web Services
