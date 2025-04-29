# AI-Thesis-Helper
Masters of Engineering in Computer Science and Engineering Project

In 2020, Generative Pre-trained Transformer (GPT), came to the mainstream and had become highly successful. In just another year it
became a game changing tool in the scientific landscape. Using GPT, various chatbots are designed. Chat-GPT in particular is by far the most used and most useful model of GPT. The model is useful in generating replies to various questions with high accuracy and usefulness. In a few years this model will develop to help people even further.

This project - AI Thesis Helper, is one such implementation of further helping students to aid their thesis writing. Many students struggle to write their thesis, as such this chat-bot can help students with various thesis tasks like idea generation. This project aims to assist students in their writing.

In the project:
- Project challenges and objectives are elaborated. 
- Prior works are looked into along with reasons for choosing GPT over other models. 
- Requirements, pros, cons and feasibility - both economic and technical along with model diagrams are dealt with. 
- Details on the dataset are discussed. 
- Fine-tuning of the model is elaborated with all details like imports, hyperparameters and training loop etc. 
- Front-end, integration and backend are discussed along with UI/UX components. 
- Implementation shows the project workings and how well it performs.

To evaluate the performance, the following metrics are utilized, model loss during training, precision, recall, F1 score, perplexity and spelling, grammar with overall writing quality. Along with a comparison of generated text, made with two other AI chatbots - ChatGPT and Perplexity AI for the same text input. Future updates are also described.

The summary of the objectives for the AI Thesis Helper are given below:
1. Answers student questions.
2. Give explanations.
3. Summarize and paraphrase paragraphs.
4. Explain paragraphs and other information.
5. Spelling and grammar checking.
6. Simple intractable interface.
7. Customizble interface.

Project challenges with choices include:
- Avaivability of Dataset - Modified "ARXIV-100" Dataset
- Framework choice - PyTorch with needed imports
- IDE - Google Colab and VScode
- Integration - Gradio framwork
- Machine training - Using colab GPU to train and fine-tune machine

The background, other details and future works of the research are throughly explained in the report.

Use case diagram
<p align="center">
  <img src= "https://github.com/user-attachments/assets/53f41776-ce32-40db-9744-14d0a84ba671"/>
</p>

Class diagram
<p align="center">
  <img src= "https://github.com/user-attachments/assets/793b7228-e6b7-4410-8f5b-e527bf0e890c"/>
</p>

Data flow diagram
<p align="center">
  <img src= "https://github.com/user-attachments/assets/9faf0db6-29a9-4934-9fa3-0a57f71ae972"/>
</p>

ER diagram
<p align="center">
   <img src= "https://github.com/user-attachments/assets/5b33a783-9ac7-4d06-901f-33d8b954a391"/>
</p>

Labelled UI/UX of AI Thesis Helper. Background button changes the background color and upgrades button just reveals a message of new features to come.

![2_All Details Labeled](https://github.com/user-attachments/assets/8d4ed102-eebf-4d3f-9bed-c4d94544c0de)

Chatbot Answer

![Transformer Rearsch Papers](https://github.com/user-attachments/assets/e5682695-3c4d-4059-b8d9-7cf5059505dc)

Results: 

- Loss during model tuning

![model loss](https://github.com/user-attachments/assets/8ff6d7ce-18bb-47f0-8383-37fb3db9202f)

- Precision, Recall and F1 score
<p align="center">
   <img src= "https://github.com/user-attachments/assets/e747ee8f-0e02-47ec-8568-ef506f3fded4"/>
</p>

- Perplexity with equation
<p align="center">
   <img src= "https://github.com/user-attachments/assets/7ce682a1-8245-43cd-8d40-d3df88d7924e"/>
</p>

- Spelling and Grammer Accuracy out of 1.0
<p align="center">
   <img src= "https://github.com/user-attachments/assets/813b1bf9-aab6-45d5-b21b-f19fe0ca1210"/>
</p>

- Comparision of Chatbots - AI Thesis Helper and ChatGPT
![ait,cgpt](https://github.com/user-attachments/assets/f8c34357-6a03-4af0-988b-dfa41f6dbeaa)

- Comparision of Chatbots - AI Thesis Helper and PerplexityAI
![ait,pai](https://github.com/user-attachments/assets/afd4f8be-a077-4927-a3bc-a5658b590d91)

All folders contain all other stuff.
