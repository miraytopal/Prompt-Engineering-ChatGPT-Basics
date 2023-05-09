# Prompt-Engineering-ChatGPT-Basics

Large language models are machine learning models that are trained on large amounts of text data to understand and generate human-like language. These models use deep learning techniques, such as neural networks, to learn the patterns and structures of language. The training process involves feeding the model with massive amounts of text data, such as books, articles, and web pages, to learn the statistical patterns of language.

Prompt engineering is the process of designing and optimizing prompts for a large language model (LLM) to achieve specific tasks or goals. LLMs are powerful artificial intelligence models that can generate human-like text, and prompt engineering is essential to ensure that the model produces accurate and relevant responses.

Prompt engineering involves several steps, including selecting the right prompts, fine-tuning the model, and testing the output.clarity is important, but clearly does not equate to short prompts in prompt engineering. The prompts can be simple or complex, depending on the task at hand. 

Overall, prompt engineering is a critical component of LLM development and is essential to ensure that the model produces accurate and relevant responses.


Parameters of Prompt
-- 
**Temperature parameter** is a crucial aspect of Large Language Models (LLMs) that determines the level of randomness and creativity in the generated text. It controls the degree of uncertainty in the model's predictions, allowing it to produce more diverse and varied outputs. A higher temperature value results in more unpredictable and imaginative responses, while a lower temperature value produces more conservative and predictable outputs.

**Top_p** is a parameter used in Large Language Models (LLMs) to control the diversity of generated text. It determines the probability threshold for selecting the next word in the generated text. The higher the Top_p value, the more diverse the generated text will be. Conversely, a lower Top_p value will result in more predictable and repetitive text.


Note: The general advice is to replace only one, not both.

Installation
--
Install the OpenAI Python library:

```
!pip install openai
```

The library needs to be configured with your account's secret key. You can find it on this [website](https://platform.openai.com/account/api-keys).

:book: **Additional Sources:** 
--
**Papers :**
- [Prompting Techniques](https://arxiv.org/pdf/2102.07350.pdf)
