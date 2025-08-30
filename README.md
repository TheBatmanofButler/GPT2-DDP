# GPT2-DDP

This is a JAX implementation of GPT-2 with data parallelism (similar to PyTorch's Distributed Data Parallel). See my [blog post](https://thebatmanofbutler.substack.com/) for more details.

To run the training script:
```
uv run scripts/train.py
```

To modify the model/training configuration, see [`gpt2ddp/core/config.py`](gpt2ddp/core/config.py).

Here's a memory profile of 16 training steps:
![73a65020-455d-4831-b825-84f72c185596_1554x924](https://github.com/user-attachments/assets/26d9d2b7-0d0e-4ca0-aed3-1074286cf367)
