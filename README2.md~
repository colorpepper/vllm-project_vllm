root@09afcccf4e0a:/home/git/rocm_vllm/benchmarks# python -m vllm.entrypoints.openai.api_server --model /home/huggingface.co/facebook_opt-125m/   --swap-space 16 --disable-log-requests



output:
RuntimeError: FlashAttention only supports AMD MI200 GPUs or newer.


# to run under baremetal:
To build vllm on ROCm 6.0 for Radeon RX7900 series (gfx1100), you should specify BUILD_FA as below:
$ docker build --build-arg BUILD_FA="0" -f Dockerfile.rocm -t vllm-rocm .
comments:but I failed @6.11

