# Using LLMs and Prompting-based approaches

## Lecture

Slides can be found here: [Week 2 Slides](https://github.com/Helsinki-NLP/LLM-course-2025/blob/main/week-2/LLM-Course%20Lecture%202.pdf).


## Preparation for the lab

**Gemini API Key**
* Use your existing google account or create a new free account
* Go to https://aistudio.google.com/apikey
* Get your API key and store it in a safe place

**Create a HuggingFace account**
* https://huggingface.co/join

**Set up Python & Jupyter environment**
* I use Python 3.12 for running code locally
* For inference or fine-tuning requiring GPU, I use Google Colab: https://colab.research.google.com/


## Lab Exercise

For this exercise use the gemini-chatbot and/or prompting-notebook found in GitHub under week-2 folder. 
Select a domain (e.g. finance, sports, cooking), tone of voice, style and persona (e.g. a pirate) and a question/task you want to accomplish (e.g. write a blog post)
* Modify the gemini-chatbot and test the different prompting approaches discussed in the lecture to achieve the task.
* Do the same for prompting-notebook (run this in Google Colab using a T4 GPU backend)
* Write a section to your report explaining what you did and what were your findings. Which prompting approach worked the best and why? 

Modify the in-context-learning notebook (you can run this locally or in Google Colab)
* Modify the prompt to change the style of the output to be a table with strengths and weaknesses in separate columns. (Markdown printing should show the table correctly. If you have time, modify the html printing to show the updated style as a table).
* If you have time: modify the notebook to use an open source model from Hugging Face instead of Gemini

