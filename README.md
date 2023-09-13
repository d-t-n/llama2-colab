# Llama2 Colab
 Implementation of Llama2 model running chat inference and fine-tuning on Google Colab notebook using one GPU only.

 ## Requirements
 To download model weights and tokenizer from Huggingface, follow these steps:

- Visit Meta AI website, accept their License: https://ai.meta.com/resources/models-and-libraries/llama-downloads/ (approval usually within 30 mins).
- Use the same email as your Huggingface account.
- After approval, visit a Llama2 Huggingface repository (like Llama2-7B): https://huggingface.co/meta-llama/Llama-2-7b-chat-hf.
- Request access again (access should be granted immediately).

 ## Data and Model
 ### The model that you want to train from the Hugging Face hub
model_name = "meta-llama/Llama-2-7b-chat-hf"
 #### The instruction dataset to use
dataset_name = "mlabonne/guanaco-llama2-1k"
