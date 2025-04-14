# The Path to Open-Sourcing the DeepSeek Inference Engine (DeepSeek-vLLM)

A few weeks ago,
during [Open Source Week](https://github.com/deepseek-ai/open-infra-index?tab=readme-ov-file#202502-open-source-week),
we open-sourced several libraries.
The response from the community has been incredibly positive - sparking inspiring collaborations, productive
discussions, and valuable bug fixes.
Encouraged by this, we’ve decided to take another step forward: contributing our internal inference engine back to the
open-source community.

We are deeply grateful for the open-source ecosystem, without which our progress toward AGI would not be possible.
Our training framework relies on [PyTorch](https://github.com/pytorch/pytorch), and our inference engine is built
upon [vLLM](https://github.com/pytorch/pytorch),
both of which have ben instrumental in accelerating the training and deployment of DeepSeek models.

Given the growing demand for deploying models like [DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3)
and [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1), we want to give back to the community as much as we can.
While we initially considered open-sourcing our full internal inference engine, we identified several challenges:

- **Codebase Divergence**: Our engine is based on an early fork of vLLM from over a year ago. Although structurally
  similar, we’ve heavily customized it for DeepSeek models, making it difficult to extend for broader use cases.
- **Infrastructure Dependencies**: The engine is tightly coupled with our internal infrastructure, including cluster
  management tools, making it impractical for public deployment without significant modifications.
- **Limited Maintenance Bandwidth**: As a small research team focused on developing better models, we lack bandwidth to
  maintain a large open-source project.

Considering these challenges, we’ve decided to collaborate with the vLLM project as a more sustainable alternative.
vLLM stands out for its broad hardware support, extensive model compatibility, and state-of-the-art performance.
Its modular architecture gives us confidence that we can adapt and contribute key components from our internal engine to
benefit the wider community.

Moving forward, we will work closely with the vLLM team to:

- **Extract Standalone Features**: Modularize and contribute reusable components as independent libraries.
- **Share Optimizations**: Contribute design improvements and implementation details directly to vLLM.

We are profoundly grateful for the open-source movement - from operating systems and programming languages to machine
learning frameworks and inference engines. It’s an honor to contribute to this thriving ecosystem and to see our models
and code embraced by the community. Together, let’s push the boundaries of AGI and ensure its benefits serve all of
humanity.

This page will serve as a central hub for tracking our related open-source efforts on the inference engine.

> [!NOTE]
> **To clarify, this article outlines our approach to open-sourcing of our DeepSeek-vLLM codebase only.
> Regarding future model releases, we maintain an open and collaborative stance towards both the open-source community
> and hardware partners.
> We commit to proactively synchronizing inference-related engineering efforts prior to new model launches, with the
> goal of enabling the community to achieve state-of-the-art (SOTA) support from Day-0. Our ultimate aim is to foster a
> synchronized ecosystem where cutting-edge AI capabilities can be seamlessly implemented across diverse hardware
> platforms upon official model releases.**
