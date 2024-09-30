# GPU-Efficient LLM Notebooks ⚡

Unlock the full potential of a T4 GPU!

This repository hosts a collection of Jupyter notebooks optimized for running large language models (LLMs) with fewer than 15 billion parameters using the [Transformers](https://huggingface.co/transformers/) library and [Accelerate](https://huggingface.co/docs/accelerate) in either `bfloat16` or `float16` precision, tailored specifically for the NVIDIA T4 GPU. Despite its modest specs, the T4 is surprisingly capable of handling these models efficiently.

## Why Use These Notebooks?

While modern LLMs often require powerful hardware, a well-optimized setup can get impressive performance even on more accessible GPUs like the T4. These notebooks are designed to help you deploy and experiment with state-of-the-art LLMs without needing top-tier hardware. Whether you're a researcher, developer, or enthusiast, this repository aims to provide practical and efficient solutions.

## Supported Language Models

The following LLMs are currently supported in this repository:

1. **Mathstral 7B** - A versatile general-purpose model for math-related tasks.
2. **Gemma 2 9B** - A robust model designed for natural language understanding and generation.
3. **CodeGemma** - A code-specific variant of Gemma, optimized for coding tasks and code completion.
4. **RecurrentGemma** - A recurrent version of the Gemma family, suited for tasks that require memory and context preservation.
5. **Mistral Nemo 12B** - A high-performance model built for more complex tasks requiring additional capacity.
6. **Llama 3.2 3B**, **Llama 3.2 1B**  - A lightweight, efficient model, perfect for small-scale tasks that need lower computational resources.

New models and updates will be added regularly as they are released. Stay tuned!

## How to Use

Each notebook includes step-by-step instructions for loading, running, and experimenting with the models using `bfloat16` or `float16` precision on a T4 GPU. For optimal performance, it's recommended to have a basic understanding of:

- [Transformers](https://huggingface.co/transformers/)
- [Accelerate](https://huggingface.co/docs/accelerate)
- Tensor optimizations for reduced precision (`bfloat16`/`float16`)

To get started, simply clone the repository and open the notebook of your choice:

```bash
git clone https://github.com/raoofaltaher/llm-notebooks
