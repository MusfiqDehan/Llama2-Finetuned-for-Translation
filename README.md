<div align="center">
    <h1>Fine-Tuned Llama-2 For Machine Translation</h1>
    <p>In this repository, I store the code for Fine Tuning Meta's Llama-2 Model for Neural Machine Translation From Bengali to English Language</p>
</div>

## Task

**Chosen Task:**<br>
Neural Machine Translation (NMT) from Bengali to English Language<br><br>
**Why I choose it?**<br>
I have been working with Neural Machine Translation for a while. For my research purpose, I am exploring different Machine Translation model. I know that we can fine tune any LLM for doing a specific task. As, I am working with Machine Translation, I want to see the performance of LLM for Machine Translation, I also have a Good Dataset. So, I think it will be a good choice for me to work on this task.

## Dataset

Base Dataset: [BUET-BanglaNMT Dataset](https://huggingface.co/datasets/csebuetnlp/BanglaNMT)(2.5 Million)<br>
Preprocessed Dataset: [Preprocessed Dataset](https://huggingface.co/datasets/musfiqdehan/preprocessed-BanglaNMT)(2.1 Million)<br><
Small Dataset: [Small Dataset](https://huggingface.co/datasets/musfiqdehan/preprocessed-BanglaNMT-sm)(200k)<br>

Why I choose this dataset?<br>
This is one of the largest Bengali to English parallel corpus available. I have format the dataset for my task, according to model. I have started working with large dataset. But for low resource and time, I have also created a small dataset for my task and fine tune the model with that dataset.

I have used the [BUET-BanglaNMT Dataset](https://huggingface.co/datasets/csebuetnlp/BanglaNMT) from HuggingFace. It contains around 2.5 million pairs of Bengali and English sentences.

## Model

I have used the [Meta's Llama-2 Model](https://huggingface.co/meta-llama/Llama-2-7b-hf) from Meta.
This is my fine-tuned adapter: [Fine-Tuned Llama-2](https://huggingface.co/musfiqdehan/Llama-2-7b-ft-mt-Bengali-to-English-sm)
