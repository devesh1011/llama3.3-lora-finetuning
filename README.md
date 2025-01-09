# Fine-Tuning with PEFT and Transformers

This project demonstrates how to fine-tune a language model using the PEFT library and Hugging Face's Transformers library.

## Requirements

To install the required dependencies, run:

```sh
pip install -r requirements.txt
```

## Fine Tuning

The fine-tuning script is located in `fine-tuning.py`. It uses the LoraConfig from the PEFT library to configure the fine-tuning process for a causal language model.

## Script Overview
**Configuration**: The script sets up the fine-tuning configuration using LoraConfig.
**Tokenizer and Model**: It loads the tokenizer and model from the Hugging Face model hub.

## Usage
To run the fine-tuning script, execute:

```python fine-tuning.py```