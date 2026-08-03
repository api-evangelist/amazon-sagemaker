# Amazon SageMaker (amazon-sagemaker)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
