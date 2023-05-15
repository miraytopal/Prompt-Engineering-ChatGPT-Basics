Prompt-Engineering-ChatGPT-Basics
--


Large language models are machine learning models that are trained on large amounts of text data to understand and generate human-like language. These models use deep learning techniques, such as neural networks, to learn the patterns and structures of language. The training process involves feeding the model with massive amounts of text data, such as books, articles, and web pages, to learn the statistical patterns of language.

Prompt engineering is the process of designing and optimizing prompts for a large language model (LLM) to achieve specific tasks or goals. LLMs are powerful artificial intelligence models that can generate human-like text, and prompt engineering is essential to ensure that the model produces accurate and relevant responses.

Prompt engineering involves several steps, including selecting the right prompts, fine-tuning the model, and testing the output.clarity is important, but clearly does not equate to short prompts in prompt engineering. The prompts can be simple or complex, depending on the task at hand. 

As a result, prompt engineering is a critical component of LLM development and is essential to ensure that the model produces accurate and relevant responses.

## Prompting Techniques

Zero-shot and few-shot prompt techniques are two of the most popular and effective ways to generate text using artificial intelligence. These techniques are based on the idea of training a language model on a small amount of data and then using it to generate text based on a prompt.

**Zero-shot prompt techniques** involve using a pre-trained language model to generate text without any additional training. This means that the model has already been trained on a large corpus of text and can generate text in a variety of styles and formats. To use a zero-shot prompt, you simply provide the model with a prompt and it will generate text based on its understanding of the language.

**Few-shot prompt techniques**, on the other hand, involve training a language model on a small amount of data before using it to generate text. This allows the model to learn specific patterns and styles of language that are relevant to the task at hand. To use a few-shot prompt, you provide the model with a small amount of training data and then use it to generate text based on a prompt.

Both zero-shot and few-shot prompt techniques have their advantages and disadvantages. Zero-shot prompts are quick and easy to use, but they may not always generate text that is relevant to the task at hand. Few-shot prompts require more training data, but they can be more accurate and generate text that is more relevant to the task.

Overall, both zero-shot and few-shot prompt techniques are powerful tools for generating text using artificial intelligence. By understanding the strengths and weaknesses of each technique, you can choose the one that is best suited to your needs and generate high-quality text that meets your specific requirements.

## Parameters of Prompt

**Temperature parameter** is a crucial aspect of Large Language Models (LLMs) that determines the level of randomness and creativity in the generated text. It controls the degree of uncertainty in the model's predictions, allowing it to produce more diverse and varied outputs. A higher temperature value results in more unpredictable and imaginative responses, while a lower temperature value produces more conservative and predictable outputs.

**Top_p** is a parameter used in Large Language Models (LLMs) to control the diversity of generated text. It determines the probability threshold for selecting the next word in the generated text. The higher the Top_p value, the more diverse the generated text will be. Conversely, a lower Top_p value will result in more predictable and repetitive text.

Note: The general advice is to replace only one, not both.

Repo Guide
-- 

1. [Basic Prompts](https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics/blob/main/notebooks/introduction_prompt_engineering.ipynb)
  - [1.1 Summarizing](https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics/blob/main/notebooks/summarizing.ipynb)
  - [1.2 Text Classification](https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics/blob/main/notebooks/text-classification-and-translation.ipynb)
  - [1.3 Translation](https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics/blob/main/notebooks/text-classification-and-translation.ipynb)
  - [1.4 Code Generation](https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics/blob/main/notebooks/code-generation-and-chatbot.ipynb)
2. [Conversation with ChatGPT](https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics/blob/main/notebooks/code-generation-and-chatbot.ipynb)

Installation
--
Install the OpenAI Python library:

```
!pip install openai
```

The library needs to be configured with your account's secret key. You can find it on this [website](https://platform.openai.com/account/api-keys).

Clone the repository from GitHub:
```
$ git clone https://github.com/miraytopal/Prompt-Engineering-ChatGPT-Basics
```
📑Sources:
-- 
- [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [Best Practices for Prompt Engineering wit OpenAI API](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)


📖**Additional Sources:** 
--
**Papers :**
- [Prompting Techniques](https://arxiv.org/pdf/2102.07350.pdf)

🤖 The texts of the examples in the repository were generated by ChatGPT.  

 [![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](https://github.com/miraytopal/Prompt-Engineering-Basics/blob/main/LICENSE) 





