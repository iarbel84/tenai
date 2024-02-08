
# Instructions for Fine-Tuning

Launch a fine-tuning flow by simply defining a base-model and dataset. 

Follow [`product-description`](./recipes/product_description/) for an example configuration that trains [`mistral-7b`](https://huggingface.co/mistralai/Mistral-7B-v0.1) to generate Amazon product descriptions.

See below for commands to train a model. You can perform full-parameter training or use LoRA.

## Training example

```shell
# Call run_sft.py and set configuration from a .yaml file

python run_sft.py recipes/product_description/config_lora.yaml
```
