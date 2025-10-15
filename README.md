# GENERATIVE-TEXT-MODEL

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: Mirza Muqaraab Ali Baig

**INTERN ID**: CT06DY2291

**DOMAIN**: Artificial Intelligence

**DURATION**: 6 WEEKS

**MENTOR**: NEELA SANTHOSH

# DESCRIPTION
This task focuses on creating an interactive AI-powered text generation tool using the GPT-2 Medium model from Hugging Face’s Transformers library. The goal is to give users a simple, web-based interface where they can type in any prompt and instantly generate coherent, creative paragraphs — almost like having a mini-ChatGPT running locally.

The project begins by importing the key libraries: PyTorch, Transformers, and Gradio. PyTorch serves as the deep learning backend that enables the GPT-2 model to run efficiently on either CPU or GPU. The Transformers library provides the pretrained GPT-2 model and tokenizer, which are essential for converting human language into tokens that the model can process and then back into readable text. Gradio, on the other hand, transforms this code into a sleek, user-friendly web app — making the model accessible even to non-technical users.

The model chosen here, GPT-2 Medium, strikes a balance between performance and computational efficiency. It’s large enough to produce meaningful and fluent text while still lightweight enough to run on most modern systems without requiring specialized hardware. The tokenizer ensures that text inputs are properly formatted before feeding them into the model.

A key component of the notebook is the generate_text() function. This function takes a user prompt and generates a single coherent paragraph based on it. It includes parameters that control how the model behaves:

• max_length defines how long the generated text can be.

• temperature adjusts the creativity of the output (lower values make the text more logical and deterministic, while higher ones add diversity and randomness).

• top_k limits the sampling pool to the top probable words, reducing incoherent outputs.

• top_p (nucleus sampling) ensures that the model considers only the most likely next words within a certain cumulative probability.

• no_repeat_ngram_size prevents the model from repeating phrases, making the text sound more natural.

Once the function is set up, Gradio is used to design an interactive interface. This interface includes a text box for entering prompts, sliders for tuning the parameters, and a clean output panel that displays the generated paragraph in Markdown format. The overall setup is visually simple but powerful — users can experiment with different creativity levels and instantly observe how the model’s tone, structure, and imagination shift.

Ultimately, this task demonstrates how to integrate a large language model into a real-time interactive application. It combines the power of pretrained NLP models with the accessibility of Gradio interfaces, making AI-driven text generation easy, fun, and customizable. Through this task, one learns not only how to harness GPT-2’s creative capabilities but also how to package machine learning models into intuitive, human-friendly tools that anyone can use.
# OUTPUT
<img width="1280" height="724" alt="Image" src="https://github.com/user-attachments/assets/9f8054f4-91c4-4d0b-81ce-63b81c577b41" />
