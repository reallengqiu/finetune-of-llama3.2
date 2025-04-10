# finetune-of-llama3.2
the code is about using lora/qlora method with image-caption dataset and huggingface, unsloth to finetune Llama-3.2-11B-Vision-Instruct

## 1. Dataset Making
First use the data_full.ipynb to deal with the original image file and the json of the image caption by making a ".arrow" file.

Or use dataset_new.ipynb to make a ".parquet" file and reload the data

## 2. Finetune
then use full_lora to finetune it!

need wandb to get report or add report_to = "none" in SFTTrainer to get the loss when training without wandb
