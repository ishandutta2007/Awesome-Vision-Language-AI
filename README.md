# Awesome-Vision-Language-AI

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Vision-Language-AI

# Top Vision-Language AI Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multimodal LLMs, Image Understanding, VQA, CLIP-Style Encoders & Language-Vision Toolkits*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Vision-Language AI**. These systems connect images (and video) with natural language—captioning, visual Q&A, document understanding, and multimodal agents.

**Examples** include OpenAI GPT-4V / GPT-4o, Google Gemini Vision, Anthropic Claude Vision, AWS Rekognition, Azure Computer Vision, Clarifai, Roboflow, Landing AI, ViSenze, Chooch AI, and **LAVIS** (`salesforce/LAVIS`)—a library for language-vision intelligence.

**Open-source emphasis**: Multimodal open weights and toolkits are advancing quickly. **LLaVA**, **InternVL**, **Qwen-VL**, **CLIP**, **LAVIS**, and **OpenCV**-based stacks enable self-hosted vision-language systems. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[OpenAI GPT-4o / vision, Google Gemini, Anthropic Claude](https://openai.com/)**  
  Frontier multimodal LLM APIs—strong image understanding, document reasoning, and tool use in a single model interface.

- **[AWS Rekognition, Azure AI Vision, Google Cloud Vision](https://aws.amazon.com/rekognition/)**  
  Managed computer vision APIs—labels, OCR, faces, moderation, and custom models without running GPUs yourself.

- **[Roboflow, Landing AI, Clarifai, Chooch, ViSenze](https://roboflow.com/)**  
  Vision platforms for dataset management, training, and deployment—often focused on classical CV plus multimodal workflows.

- **[Other commercial vision-language platforms](https://www.anthropic.com/)**  
  Additional enterprise multimodal and industry-specific vision services.

## Open-Source GitHub Projects

### Multimodal LLMs & Assistants

- **[LLaVA](https://github.com/haotian-liu/LLaVA)**  
  Influential open Large Language and Vision Assistant—visual instruction tuning blueprint used by many follow-on models.

- **[InternVL](https://github.com/OpenGVLab/InternVL)**  
  Strong open multimodal model family—competitive document, OCR, and high-resolution understanding among open weights.

- **[Qwen-VL / Qwen2-VL series](https://github.com/QwenLM/Qwen2-VL)**  
  Open-weight vision-language models from Alibaba—multilingual multimodal capability and active ecosystem.

- **[OpenFlamingo / IDEFICS-style projects](https://github.com/mlfoundations/open_flamingo)**  
  Open attempts to reproduce Flamingo-style few-shot vision-language learning.

- **[MiniGPT / community LLaVA variants](https://github.com/search?q=LLaVA+OR+vision+language+model)**  
  Smaller and specialized open VLM fine-tunes for edge and domain tasks.

### Libraries, Encoders & Toolkits

- **[LAVIS](https://github.com/salesforce/LAVIS)**  
  Salesforce’s open library for language-vision intelligence—unified APIs for captioning, VQA, retrieval, and foundation model research.

- **[OpenCLIP](https://github.com/mlfoundations/open_clip)**  
  Open implementation of CLIP-style contrastive vision-language encoders—training recipes and many pretrained checkpoints.

- **[CLIP (OpenAI original)](https://github.com/openai/CLIP)**  
  Foundational open contrastive image-text model—still widely used as a vision backbone for multimodal systems.

- **[Transformers (Hugging Face multimodal)](https://github.com/huggingface/transformers)**  
  Standard open library with dozens of vision-language model implementations and processors.

- **[OpenCV](https://github.com/opencv/opencv)**  
  Classic open computer vision library—preprocessing, classical CV, and deployment helpers alongside modern VLMs.

- **[Detectron2 / MMDetection + LLM bridges](https://github.com/facebookresearch/detectron2)**  
  Open detection/segmentation stacks often composed with language models for grounded vision tasks.

- **[Roboflow open tools / supervision](https://github.com/roboflow/supervision)**  
  Open utilities for vision pipelines, annotation visualization, and deployment helpers.

### Additional Strong Open-Source Options

- **General open VLM**: LLaVA or InternVL family.
- **Strong open-weight multimodal**: Qwen-VL series.
- **Research toolkit**: LAVIS + Hugging Face Transformers.
- **Encoders**: OpenCLIP / CLIP.
- **Composable stacks**: Vision encoder → projector → LLM (LLaVA pattern); or API (GPT-4o/Gemini) for highest accuracy with less ops.
- Commercial APIs still lead for frontier reasoning quality, safety tooling, and zero-ops scale.

**Frameworks for building custom systems**:  
**LLaVA** / **InternVL** / **Qwen-VL** for open multimodal chat; **LAVIS** and **Transformers** for experimentation; **OpenCLIP** for retrieval and embeddings.  
Fully open vision-language stacks are production-viable for many apps; frontier accuracy often still uses commercial multimodal APIs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Vision-language models can misread images, leak training biases, or be unsafe on sensitive content. Validate critical decisions with humans. Respect privacy—faces, documents, and medical images may be regulated.
- Open weights offer control and on-prem options but need GPU ops and evaluation. Commercial APIs shift infrastructure and often safety filters to the vendor. Neither replaces domain validation and responsible deployment.

---

**Made for multimodal ML engineers, product teams, and researchers connecting vision with language.**  
Let's expand open vision-language AI while recognizing the frontier capability that leading commercial multimodal platforms deliver.
