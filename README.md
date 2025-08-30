# GPT2-DDP

This is a JAX implementation of GPT-2 with data parallelism (similar to PyTorch's Distributed Data Parallel). See [blog post](https://thebatmanofbutler.substack.com/) for more details.

To run the training script:
```
uv run scripts/train.py
```

To modify the model/training configuration, see [`gpt2ddp/core/config.py`](gpt2ddp/core/config.py).

Here's a memory profile of 16 training steps:
