# Text Generation with GPT-2
### Generative AI Internship – Prodigy InfoTech (GA Track)

## About this Project
For my **Generative AI internship at Prodigy InfoTech**, I worked on **Task 1: Text Generation using GPT-2**.  
The goal was to fine-tune a pre-trained GPT-2 model on a small custom dataset and see how well it could generate coherent and contextually relevant text.

This was my first hands-on experience with **Generative AI**, and I learned a lot about how modern AI models work!

---

## What is GPT-2?
GPT-2 is a language model built by OpenAI that can generate human-like text.  
It predicts the next word in a sequence based on the words before it. By fine-tuning it on our own dataset, we can teach it to generate text in a style we want.

---

## What I Set Out to Do
- Fine-tune GPT-2 on my custom dataset  
- Generate text from prompts  
- Learn how pre-trained models can be adapted for specific tasks  
- Get hands-on experience with transformers and NLP workflows  

---

## Dataset
- File: `data.txt`  
- Contains short sentences about AI, technology, or any topic I chose  
- Used to teach GPT-2 the style and structure of my data

---

## Tools & Technologies
- **Python**  
- **Hugging Face Transformers**  
- **PyTorch**  
- **Datasets library**  
- **Google Colab**  

---

## How I Implemented It
1. Installed all required libraries in Colab  
2. Loaded GPT-2 tokenizer and model  
3. Set `tokenizer.pad_token = tokenizer.eos_token` to fix padding issues  
4. Tokenized my dataset and added `labels = input_ids` so the model could compute loss  
5. Fine-tuned GPT-2 for 2 epochs  
6. Generated sample text from a prompt  

---

## Sample Output
**Prompt:**  
> The future of artificial intelligence  

**Generated Text:**  
> The future of artificial intelligence is shaping the way machines interact with humans and solve complex problems by learning from data and experience.

*(Text may vary depending on the random generation)*

---

## Project Structure

---

## Key Takeaways
- Learned how to fine-tune pre-trained GPT-2 models  
- Understood tokenization and padding for transformers  
- Learned how Hugging Face Trainer computes loss  
- Got practical exposure to **Generative AI workflows**

---

## Internship Info
- **Track Code:** GA (Generative AI)  
- **Organization:** Prodigy InfoTech  
- **Duration:** 15 Jan – 15 Feb 2026  

---

This task was a fun and valuable way to **get hands-on with AI** and understand how these models work in real-world projects. I’m excited to move on to the next task and keep learning!  

