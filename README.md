# Amazon SageMaker (amazon-sagemaker)

Amazon SageMaker is a fully managed machine learning platform that enables developers and data scientists to build, train, and deploy machine learning models at scale. SageMaker removes the heavy lifting from each step of the machine learning process, providing built-in algorithms, managed Jupyter notebooks, distributed training, automatic model tuning, and one-click deployment to production endpoints with auto-scaling.

**APIs.json:** [https://aws.amazon.com/sagemaker/](https://aws.amazon.com/sagemaker/)

## Tags

- AI
- AWS
- Inference
- Machine Learning
- MLOps
- Training

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Amazon SageMaker API

The Amazon SageMaker control plane API for creating and managing SageMaker resources including notebook instances, training jobs, models, endpoints, pipelines, experiments, feature groups, and monitoring schedules.

- **Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html)
- **Base URL:** `https://api.sagemaker.{region}.amazonaws.com`

#### Tags

- Machine Learning
- AI
- Training
- Inference

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-sagemaker-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amazon-sagemaker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-sagemaker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/amazon-sagemaker-notebook-instance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-sagemaker-training-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-sagemaker-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-sagemaker-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [SDK](https://pypi.org/project/sagemaker/)
- [Code Examples](https://github.com/aws/amazon-sagemaker-examples)

### Amazon SageMaker Runtime API

The Amazon SageMaker AI runtime API for invoking deployed model endpoints to get real-time inference predictions.

- **Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html](https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html)
- **Base URL:** `https://runtime.sagemaker.{region}.amazonaws.com`

#### Tags

- Inference
- Runtime
- Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/API_runtime_InvokeEndpoint.html)
- [Postman Collection](collections/amazon-sagemaker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-sagemaker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon SageMaker Feature Store Runtime API

Data plane API operations for the Amazon SageMaker Feature Store supporting put, delete, and retrieve operations for ML features.

- **Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html)
- **Base URL:** `https://featurestore-runtime.sagemaker.{region}.amazonaws.com`

#### Tags

- Feature Store
- Machine Learning
- Data

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Feature_Store_Runtime.html)
- [Postman Collection](collections/amazon-sagemaker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-sagemaker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon SageMaker Metrics Service API

Data plane API operations for Amazon SageMaker Metrics for putting and retrieving metrics related to training runs.

- **Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html)
- **Base URL:** `https://metrics.sagemaker.{region}.amazonaws.com`

#### Tags

- Metrics
- Training
- Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_Metrics_Service.html)
- [Postman Collection](collections/amazon-sagemaker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-sagemaker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon SageMaker Geospatial API

APIs for creating and managing Amazon SageMaker geospatial capabilities including earth observation jobs and vector enrichment jobs.

- **Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html)
- **Base URL:** `https://sagemaker-geospatial.{region}.amazonaws.com`

#### Tags

- Geospatial
- Machine Learning
- AWS

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_SageMaker_geospatial_capabilities.html)
- [Postman Collection](collections/amazon-sagemaker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-sagemaker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon SageMaker Edge Manager API

SageMaker Edge Manager dataplane service for communicating with active edge agents running ML models on edge devices.

- **Human URL:** [https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html)
- **Base URL:** `https://edge.sagemaker.{region}.amazonaws.com`

#### Tags

- Edge
- IoT
- Machine Learning

#### Properties

- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/APIReference/API_Operations_Amazon_Sagemaker_Edge.html)
- [Postman Collection](collections/amazon-sagemaker.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-sagemaker.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://aws.amazon.com/)
- [Getting Started](https://aws.amazon.com/sagemaker/getting-started/)
- [Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/)
- [API Reference](https://docs.aws.amazon.com/sagemaker/latest/APIReference/)
- [Console](https://console.aws.amazon.com/sagemaker/)
- [Sign Up](https://portal.aws.amazon.com/billing/signup)
- [Pricing](https://aws.amazon.com/sagemaker/pricing/)
- [F A Q](https://aws.amazon.com/sagemaker/faqs/)
- [Blog](https://aws.amazon.com/blogs/machine-learning/)
- [Status Page](https://status.aws.amazon.com/)
- [Support](https://aws.amazon.com/support/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [Security](https://docs.aws.amazon.com/sagemaker/latest/dg/security.html)
- [Compliance](https://aws.amazon.com/compliance/)
- [GitHub Organization](https://github.com/aws)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/amazon-sagemaker)
- [Knowledge Center](https://repost.aws/knowledge-center)
- [C L I](https://docs.aws.amazon.com/cli/latest/reference/sagemaker/)
- [C L I](https://github.com/aws/sagemaker-hyperpod-cli)
- [SDK](https://github.com/aws/sagemaker-python-sdk)
- [GitHub Repository](https://github.com/aws/sagemaker-core)
- [GitHub Repository](https://github.com/aws/sagemaker-distribution)
- [Spectral Rules](rules/amazon-sagemaker-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-sagemaker-vocabulary.yaml)
- [Training](https://aws.amazon.com/training/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [JSON-LD](json-ld/amazon-sagemaker-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/amazon-sagemaker-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/amazon-sagemaker-endpoint-structure.json)
- [JSON Structure](json-structure/amazon-sagemaker-model-structure.json)
- [JSON Structure](json-structure/amazon-sagemaker-notebook-instance-structure.json)
- [JSON Structure](json-structure/amazon-sagemaker-tag-structure.json)
- [JSON Structure](json-structure/amazon-sagemaker-training-job-structure.json)
- [Example](examples/amazon-sagemaker-endpoint-example.json)
- [Example](examples/amazon-sagemaker-model-example.json)
- [Example](examples/amazon-sagemaker-notebook-instance-example.json)
- [Example](examples/amazon-sagemaker-tag-example.json)
- [Example](examples/amazon-sagemaker-training-job-example.json)
- [Integrations](https://aws.amazon.com/partners/)
