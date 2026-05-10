This repo implement a CUDA version of GPT2 by replacing all computation kernels in the PyTorch's implementation of GPT2 with our customized CUDA kernels.
Implementation details can be found at project_report/ml_sys_final_project_report_xz4863_.pdf

CUDA kernels as well as the wrapper definiton for Python is in /src
test_gpt2_model.py implements the GPT2 with our CUDA kernels and runs test cases, with the BtenGPT2LMHeadModel class being the GPT2 implementation.


