# Amazon SageMaker (amazon-sagemaker)
Amazon SageMaker is a fully managed machine learning platform that enables developers and data scientists to build, train, and deploy machine learning models at scale. SageMaker removes the heavy lifting from each step of the machine learning process, providing built-in algorithms, managed Jupyter notebooks, distributed training, automatic model tuning, and one-click deployment to production endpoints with auto-scaling.

**URL:** [Visit Amazon SageMaker](https://aws.amazon.com/sagemaker/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AI, AWS, Inference, Machine Learning, MLOps, Training

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Amazon SageMaker API
The Amazon SageMaker control plane API for creating and managing SageMaker resources including notebook instances, training jobs, models, endpoints, pipelines, experiments, feature groups, and monitoring schedules.

**Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html)

#### Tags:

 - Machine Learning, AI, Training, Inference

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-sagemaker-openapi.yml)
- [JSONSchema - Notebook Instance](json-schema/amazon-sagemaker-notebook-instance-schema.json)
- [JSONSchema - Training Job](json-schema/amazon-sagemaker-training-job-schema.json)
- [JSONSchema - Model](json-schema/amazon-sagemaker-model-schema.json)
- [JSONSchema - Endpoint](json-schema/amazon-sagemaker-endpoint-schema.json)
- [Python SDK](https://pypi.org/project/sagemaker/)
- [Jupyter Notebook Examples](https://github.com/aws/amazon-sagemaker-examples)

### Amazon SageMaker Runtime API
The Amazon SageMaker AI runtime API for invoking deployed model endpoints to get real-time inference predictions.

**Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html](https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html)

#### Tags:

 - Inference, Runtime, Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html)

### Amazon SageMaker Feature Store Runtime API
Data plane API operations for the Amazon SageMaker Feature Store supporting put, delete, and retrieve operations for ML features.

**Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html)

#### Tags:

 - Feature Store, Machine Learning, Data

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html)

### Amazon SageMaker Metrics Service API
Data plane API operations for Amazon SageMaker Metrics for putting and retrieving metrics related to training runs.

**Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html)

#### Tags:

 - Metrics, Training, Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html)

### Amazon SageMaker Geospatial API
APIs for creating and managing Amazon SageMaker geospatial capabilities including earth observation jobs and vector enrichment jobs.

**Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html)

#### Tags:

 - Geospatial, Machine Learning, AWS

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html)

### Amazon SageMaker Edge Manager API
SageMaker Edge Manager dataplane service for communicating with active edge agents running ML models on edge devices.

**Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html)

#### Tags:

 - Edge, IoT, Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [GettingStarted](https://aws.amazon.com/sagemaker/getting-started/)
- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/)
- [APIReference](https://docs.aws.amazon.com/sagemaker/latest/APIReference/)
- [Console](https://console.aws.amazon.com/sagemaker/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Pricing](https://aws.amazon.com/sagemaker/pricing/)
- [FAQ](https://aws.amazon.com/sagemaker/faqs/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/)
- [StatusPage](https://status.aws.amazon.com/)
- [Support](https://aws.amazon.com/support/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Security](https://docs.aws.amazon.com/sagemaker/latest/dg/security.html)
- [Compliance](https://aws.amazon.com/compliance/)
- [GitHubOrganization](https://github.com/aws)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-sagemaker)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/sagemaker/)
- [SageMaker HyperPod CLI](https://github.com/aws/sagemaker-hyperpod-cli)
- [Training](https://aws.amazon.com/training/)

## Features

| Name | Description |
|------|-------------|
| SageMaker Studio | Fully integrated development environment for ML work with notebooks, debugging, and experiment tracking. |
| SageMaker HyperPod | Purpose-built infrastructure for distributed training that reduces foundation model training time by up to 40%. |
| SageMaker JumpStart | Hub providing access to foundation models, pre-built algorithms, and one-click deployment. |
| SageMaker Autopilot | Automated model creation with complete visibility and transparency. |
| SageMaker Canvas | No-code visual interface for creating ML models without writing code. |
| SageMaker Feature Store | Store, share, and manage features for machine learning models. |
| SageMaker Data Wrangler | Data preparation tool that reduces transformation workflow time significantly. |
| SageMaker Ground Truth | Incorporates human feedback throughout the ML lifecycle for data labeling. |
| SageMaker Pipelines | Purpose-built CI/CD service for machine learning workflows. |
| SageMaker Model Monitor | Automatically detects concept drift and data quality issues in deployed models. |
| SageMaker Clarify | Provides machine learning explainability and bias detection. |
| SageMaker Experiments | Streamlines tracking and management of ML experiments. |
| ML Governance | Access controls and transparency across the full ML lifecycle with audit trails. |

## Use Cases

| Name | Description |
|------|-------------|
| Generative AI Applications | Build custom generative AI applications using proprietary data with foundation model fine-tuning. |
| ML Model Development | Train and deploy ML models across the entire machine learning lifecycle from exploration to production. |
| Data Analytics | Query and analyze data across unified sources with built-in SQL analytics and data processing. |
| Enterprise AI Governance | Manage data and AI artifacts with fine-grained security controls and compliance tooling. |
| Computer Vision | Build and deploy computer vision models for image classification, object detection, and segmentation. |
| Natural Language Processing | Train and deploy NLP models for text classification, entity recognition, and language generation. |
| Fraud Detection | Build real-time fraud detection models with low-latency inference endpoints. |
| Predictive Maintenance | Deploy ML models on edge devices for predictive maintenance use cases. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Store training data, model artifacts, and inference outputs in Amazon S3 data lakes. |
| Amazon Redshift | Zero-ETL integration for near real-time data ingestion from Redshift warehouses. |
| Amazon ECR | Store and manage Docker containers for custom training and inference environments. |
| AWS Lambda | Trigger ML inference pipelines and post-processing workflows with Lambda functions. |
| Amazon EventBridge | Trigger SageMaker pipelines and workflows based on events. |
| AWS Step Functions | Orchestrate multi-step ML workflows using Step Functions state machines. |
| Apache Iceberg | Lakehouse architecture supporting Apache Iceberg-compatible data tools. |
| Amazon DataZone | SageMaker Catalog built on Amazon DataZone for data discovery and governance. |
| Amazon Q Developer | Natural language assistance integrated into SageMaker Unified Studio. |
| Hugging Face | Deploy Hugging Face models directly via SageMaker JumpStart. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon SageMaker API](openapi/amazon-sagemaker-openapi.yml)

### JSON Schema

- [NotebookInstance](json-schema/amazon-sagemaker-notebook-instance-schema.json)
- [TrainingJob](json-schema/amazon-sagemaker-training-job-schema.json)
- [Model](json-schema/amazon-sagemaker-model-schema.json)
- [Endpoint](json-schema/amazon-sagemaker-endpoint-schema.json)
- [Tag](json-schema/amazon-sagemaker-tag-schema.json)

### JSON Structure

- [NotebookInstance](json-structure/amazon-sagemaker-notebook-instance-structure.json)
- [TrainingJob](json-structure/amazon-sagemaker-training-job-structure.json)
- [Model](json-structure/amazon-sagemaker-model-structure.json)
- [Endpoint](json-structure/amazon-sagemaker-endpoint-structure.json)

### JSON-LD

- [Amazon SageMaker Context](json-ld/amazon-sagemaker-context.jsonld)

### Examples

- [NotebookInstance Example](examples/amazon-sagemaker-notebook-instance-example.json)
- [TrainingJob Example](examples/amazon-sagemaker-training-job-example.json)
- [Model Example](examples/amazon-sagemaker-model-example.json)
- [Endpoint Example](examples/amazon-sagemaker-endpoint-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon SageMaker API](capabilities/shared/amazon-sagemaker.yaml) — 13 operations for notebook, training, model, and endpoint management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [ML Lifecycle Management](capabilities/ml-lifecycle-management.yaml) | Amazon SageMaker | 10 | ML Engineer, Data Scientist |

## Vocabulary

- [Amazon SageMaker Vocabulary](vocabulary/amazon-sagemaker-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon SageMaker Spectral Rules](rules/amazon-sagemaker-spectral-rules.yml) — 22 rules across 9 categories enforcing Amazon SageMaker API conventions

## Maintainers

**FN:** Kin Lane
