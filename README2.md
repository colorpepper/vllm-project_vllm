root@09afcccf4e0a:/home/git/rocm_vllm/benchmarks# python -m vllm.entrypoints.openai.api_server --model /home/huggingface.co/facebook_opt-125m/   --swap-space 16 --disable-log-requests



output:
RuntimeError: FlashAttention only supports AMD MI200 GPUs or newer.
