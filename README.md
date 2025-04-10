# finetune-of-llama3.2
the code is about using lora/qlora method with image-caption dataset and huggingface, unsloth to finetune Llama-3.2-11B-Vision-Instruct

first use the data_full.ipynb to deal with the original image file and the json of the image caption.

then use lora_full to finetune it!

need wandb to get report or add report_to = "none" in SFTTrainer to get the loss when training without wandb
