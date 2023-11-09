# 🧑‍🔬 Tabby Registry

## Completion models (`--model`)

We recommend using

* For **1B to 3B models**, it's advisable to have at least **NVIDIA T4, 10 Series, or 20 Series GPUs**.
* For **7B to 13B models**, we recommend using **NVIDIA V100, A100, 30 Series, or 40 Series GPUs**.

| Model ID | License |
| -------- | ------- |
| [wsxiaoys/DeepseekCoder-1.3B](https://huggingface.co/deepseek-ai/deepseek-coder-1.3b-base) | [Deepseek License](https://github.com/deepseek-ai/deepseek-coder/blob/main/LICENSE-MODEL) |
| [wsxiaoys/DeepseekCoder-6.7B](https://huggingface.co/deepseek-ai/deepseek-coder-6.7b-base) | [Deepseek License](https://github.com/deepseek-ai/deepseek-coder/blob/main/LICENSE-MODEL) |


## Chat models (`--chat-model`)

To ensure optimal response quality, and given that latency requirements are not stringent in this scenario, we recommend using a model with at least 3B parameters.

| Model ID | License |
| -------- | ------- |
| [wsxiaoys/Yi-34B](https://huggingface.co/01-ai/Yi-34B) | [Yi License](https://huggingface.co/01-ai/Yi-34B/blob/main/LICENSE) |
| [wsxiaoys/OpenHermes-2.5-Mistral-7B](https://huggingface.co/teknium/OpenHermes-2.5-Mistral-7B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
