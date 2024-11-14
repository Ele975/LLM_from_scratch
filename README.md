# LLM_from_scratch

Implementation and fine-tuning of a LLM like GPT-2 in Google Colab from scratch step by step using Pytorch.

The repository consists of three files:
1. Pretraining of the LLM model to learn how to predict the next token in a coherent way. Dataset comes from 'the-verdict.txt'.
2. Fine-tuning for classification: fine-tuning of the implemented LLM in step 1 downloading official pretrained weights of GPT-2. The classification task is to determine if an e-mail is spam or not given the e-mail text as input. Despite LLMs are in general not used for such tasks, this is for demonstration purposes only. Dataset used: SMS spam collection.
3. Instruction fine-tuning: fine-tuning of the implemented LLM in step 1 such that it is able to process and to understand some instructions given to it as natural text and it outputs coherent responses. Dataset used: 'instruction data' dataset from the book 'Build a large language model from scratch', Sebastian Raschka.
