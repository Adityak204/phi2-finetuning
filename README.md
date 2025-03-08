# Fine-tune Phi-2 using QLoRA
- This repository contains the code for fine-tuning the `microsoft/phi-2` model using QLoRA on `OpenAssistant/oasst1` dataset.
- `bitsandbytes` is used for 4bit quantization of the model.
- Fine tuning has been done for 300 steps on Kaggle P100 GPU.

## Requirements
- bitsandbytes
- transformers
- torch
- trl
- peft