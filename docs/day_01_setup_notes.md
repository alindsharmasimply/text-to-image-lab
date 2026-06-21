# Day 1 Setup Notes

## Hardware
- CUDA available: No
- GPU name: NA
- Will I use local GPU or Colab? Neither. I'll use local CPU.

## Environment
- Python version: 3.12.3
- PyTorch version: 2.12.1+cu130
- TorchVision version: 0.27.1+cu130

## What I learned
- Why GPU matters for diffusion: GPUs matter due to their massive parallel-processing power and specialized memory. Text-based AI models which process one token at a time. CPUs are sequential processors designed for general-purpose tasks. GPUs contain thousands of tiny cores designed to do the same math at the exact same time.

## Problems encountered
- At a few places on reddit it was suggested that one should install Pytorch globally rather than a virtual environment but I went ahead with a virtual environment only.
- Also I can see there is a usage of 'conda' package for setting up environments and installations at majority of places but I'm proceeding with the light-weight 'venv' only.