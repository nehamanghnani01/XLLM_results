# XLLM_results

The goal is to find ways to optimize LLM's inference and performance. 
This repository contains results from the experiments conducted on the Meta Llama2 model. 

The .ipynb file has the results of quantization for 
- absmax quantization
- zeropoint quantization
- int 8 quantization
- int 4 quantization.

For the different quantized models developed from the Llama 2 model, the notebook contains results for 
- text generation given a prompt
- perplexity of the generated text
- token generation for the c4 dataset
- perplexity of the c4 dataset with the different quantized models

