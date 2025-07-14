# GENERATIVE-TEXT-MODEL

COMPANY : CODTECH IT SOLUTIONS

NAME : KODURU LOHITHA

INTERN ID : CITS0D62

DOMAIN : Artificial Intelligence

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH

** DESCRIPTION OF TASK 3:

In Task 4 of the internship, I worked on building a Text Generation model using GPT-2 (Generative Pre-trained Transformer 2), a powerful and popular transformer-based language model developed by OpenAI. The objective of this task was to create a system that takes a user-provided sentence or prompt and automatically generates a coherent and contextually relevant paragraph based on that input. This task was performed using Jupyter Notebook with the Python kernel, and it involved using key tools such as the Transformers library by Hugging Face, PyTorch, and GPT-2.

Text generation is one of the core applications of Natural Language Processing (NLP). Unlike summarization or translation tasks, text generation requires the model to understand the context of a given input and continue it meaningfully with new content. GPT-2 is particularly suited for this task because it has been trained on a massive dataset comprising a wide range of topics from the internet. As a result, it can generate human-like text with surprising fluency and relevance.

In this task, I used Hugging Face’s pipeline() API to load the pre-trained GPT-2 model with minimal code. The task flow involved importing the required functions, loading the model, setting a random seed for reproducibility, and then taking a prompt from the user. The model uses that prompt as a seed to generate text using the generator() function. I configured the model to generate a maximum of 150 new tokens and return a single output. Once the generation was complete, the result was displayed directly in the notebook.

One of the key aspects I learned while working on this task was how transformers work under the hood. GPT-2 is a decoder-only transformer that predicts the next word in a sequence based on the previous context. It uses attention mechanisms to assign weight to the most relevant words during generation. This allows GPT-2 to produce text that is contextually aligned and grammatically coherent. I also explored parameters such as temperature, top_k, and max_new_tokens to understand how they affect the randomness, creativity, and length of the output.

Text generation models like GPT-2 have practical applications across many industries. They are used in creative writing tools, chatbots, content generation platforms, and code assistants. For example, AI-based writing platforms can suggest content for blogs, social media posts, and marketing emails. GPT-2 is also used in tools like Notion AI, Jasper AI, and GitHub Copilot to enhance productivity in writing and coding tasks. Text generation also plays a role in educational apps, where it can provide explanations, generate quizzes, or offer writing suggestions to students.

The tools I used in this task included:

Python: for coding and interaction

Jupyter Notebook: as the IDE for running and testing code

Transformers library: to load and use GPT-2 with ease

PyTorch: as the backend engine supporting model inference

This task not only strengthened my coding skills but also deepened my understanding of large language models and how they are reshaping human-computer interaction. I learned the importance of prompt engineering, which involves crafting effective prompts to guide the model in producing relevant results. I also saw how powerful transformer models can be, especially when used in user-facing applications.

Overall, Task 4 gave me hands-on experience with real-world NLP, helped me understand the behavior of generative models, and taught me how to leverage pre-trained models to build intelligent applications with minimal effort and high effectiveness.

