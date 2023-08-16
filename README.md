# Explanation and Game – Play Capabilities of Modern AI and LLMs

<a href="https://www.bing.com/create?toWww=1&redig=2C515D4EAC1C4E42A8570BD3DA3B6064">
   <img src="https://github.com/ZerksisMistry/Project_GPT-3.5_LLM/blob/6063e985a93482b0a1f3fa74da4aebe3fd392688/Extras/GitHub_Picture.png" 
      width="840" height="290"/">
</a>

## 🤖 Introduction 
 
<p align="justify">
This repository has the information and the code that I have used in my experimentation and writing my dissertation for my MSc in Advanced Computer Science with AI. Overall, my project, titled "Explanation and Game-Play Capabilities of Modern AI and Large Language Models (LLMs)", delves into the capabilities of advanced and most recently introduced LLMs. It examines their performance across diverse prompts, use-cases, and notably, in strategic gameplay, highlighting their proficiency in providing detailed explanations.   
</p>

<p align="justify">
   
This documentation presents the development and exploration of a chatbot powered by OpenAI's GPT-3.5 (`text-davinci-003 engine`), specifically designed for strategic gameplay analysis and automation tasks. Throughout our study, we experimented with zero-shot, one-shot, and few-shot prompting techniques to analyse the explainable capabilities of the OpenAI's GPT-3.5 LLM. By harnessing these different approaches, the chatbot not only offers insightful strategic gameplay explanations but also showcases its prowess in automating various tasks and interactions.  

</p>

## 📚 Project Resources
<p align="justify">
Our project, meticulously developed within a Google Colab environment, showcases the versatile capabilities of the GPT-3.5 LLM in diverse scenarios and tasks.
</p>

`Project.ipynb`: This is our main notebook with all our project experimentations leveraging the capabilities of GPT-3.5 LLM. 

### 🌟 Features
   
- 🖋 **Prompt-Based Interactions:**  <p align="justify"> The code encompasses distinct use-cases for zero-shot, one-shot, and few-shot prompting, exhibiting the vast scope of GPT-3.5 LLM interactions. It also includes interactive features for the user to continue the conversation with their follow-up prompts or end the conversation. </p>

- 🎮  **Interactive Gameplay Demonstrations:** <p align="justify"> Engage with the LLM in strategic and logical games like Tic-Tac-Toe, Connect-Four, and Chess, observing its gameplay strategies and decision-making. </p>

- 🧮 **Automation Tasks:** <p align="justify"> Explore our mathematical automation tasks, purposefully designed to showcase GPT-3.5's capabilities in responding to the zero-shot prompts. Witness its capability to generate examples mirroring the provided zero-shot prompts, autonomously solve them, and subsequently validate its own solutions. </p>
  
- 🧩 **Modular Code Design:** <p align="justify"> Our code is structured for clarity, adaptability, and ease of understanding, ensuring users can follow along and modify as needed. </p>
  
- 💡 **Detailed Comments:** <p align="justify"> Navigate through our code effortlessly with the aid of comprehensive comments, providing context and clarity for each block of code. </p>

### Link to Colab:

<a href="https://colab.research.google.com/drive/1e0pEE_1bHZnPKVEnh9TGhmUWwg4T9gpk?usp=sharing">
   <img src="https://github.com/ZerksisMistry/Project_GPT-3.5_LLM/blob/6063e985a93482b0a1f3fa74da4aebe3fd392688/Extras/Google%20Colab%20Logo.png" alt="Google Colab Logo" width="100" height="50"/>
</a>

[Google Colab Notebook - Project](https://colab.research.google.com/drive/1e0pEE_1bHZnPKVEnh9TGhmUWwg4T9gpk?usp=sharing)


## 💻 Requirements and Setup

**Prerequisites:**

The notebook was developed in the Colab Jupyter Environment.

- Python (version 3.x recommended).
- Necessary libraries and dependencies as listed in the Colab Notebook.
- OpenAI Python client.


**Installation:**

```
git clone [gh repo clone ZerksisMistry/Project_GPT-3.5_LLM]

!pip install openai        # for the use of OpenAI API Key
!pip install python-chess  # for chess board representation
```

**OpenAI API Setup:**

```
import openai

openai.api_key = 'YOUR_OPENAI_API_KEY'
```

Replace `YOUR_OPENAI_API_KEY` with your OpenAI API Key.

**Usage:**

To engage with the AI chatbot and delve deep into its strategic gameplay insights:
- Open the Google Colab notebook.
- Execute the cells in sequence.
- Use your OpenAI API Key in the respective area to leverage the capabilities of the LLM.
- Experience the chatbot system powered by GPT-3.5 LLM for prompts and automation tasks.
- Experience the AI's strategic gameplay prowess in the interactive sections.


**Tokenization with TikToken:**

Leverage OpenAI's [TikToken Tokenizer](https://github.com/openai/tiktoken) for efficient token counting within text strings.


## 📌 Presentation Highlights
<p align="justify"> 
Embark on a journey through our comprehensive exploration of various Large Language Models (LLMs). We've delved deep into models such as GPT-4, Google Bard, Claude-2, and LLaMA-2, emphasizing their capabilities with zero-shot prompts. A special focus has been laid on GPT-3.5, assessing its performance across zero-shot, one-shot, and few-shot prompts, as well as its application in automation tasks and interactive gameplay.
</p>

**Research Objectives:** Our core mission - assessing LLMs for gameplay and explanatory prowess.

**Literature Summary:**

- **Historical Overview:** <p align="justify"> From the Turing Test's inception to today's advances, chart the journey of machine comprehension.</p>
- **Research Gap:** <p align="justify"> Our study targets an unexplored niche: LLMs' strategy and self-explanation in games.</p>
- **LLM Impact:** <p align="justify"> Recent literature underscores LLMs' transformative potential across varied sectors.</p>
- **Explainability in AI:** <p align="justify"> AI's explainability is emerging, but methods to assess LLMs need to be more comprehensive for better understanding of the capabilities of the LLMs.</p>
- **Towards AGI:** <p align="justify"> Lastly, discussions about Artificial General Intelligence, or AGI, are abundant but often speculative. The literature revealed a need for empirical evidence to support claims and theories about AGI’s potential and challenges.</p>

**Methodology:** <p align="justify"> Methodology encompasses diverse LLM evaluations, strategic gameplay tests, zero-shot maths task automations, in-depth GPT-3.5 prompt assessments, specific evaluation metrics, and insights into OpenAI's LLM framework.</p>

**Analysis:** <p align="justify"> In-depth evaluation of gameplay strategies and explanatory capabilities of LLMs.</p>

**Proposed OpenAI Framework:** <p align="justify"> Unveil our tailored framework for understanding OpenAI API interactions.</p>

<img src="https://github.com/ZerksisMistry/Project_GPT-3.5_LLM/blob/6063e985a93482b0a1f3fa74da4aebe3fd392688/Extras/OpenAI%20API%20Framework.png" 
   width="700" height="500" alt="OpenAI Framework">

**Conclusion & Recommendations:** <p align="justify"> Enlisted key findings and our propositions for the broader AI ecosystem.</p>


## Licensing Information

<p align="justify">
   
This repository contains various documents and files related to our comprehensive research on Large Language Models (LLMs) and their applications. While the primary content, including the `Project.ipynb`, Project_Presentation, and other associated files, are distributed under the `Open Software License 3.0 (OSL 3.0)`, it's essential to be aware of the specific licensing terms.

</p>

<p align="justify">
   
The detailed licensing terms governing this repository can be found in the `LICENSE.txt` file. We urge all users, contributors, and researchers accessing our work to thoroughly review the `LICENSE.txt` to ensure a clear understanding of the rights and limitations it imposes.

</p>

<p align="justify">
Your respect for the licensing terms is crucial in acknowledging the efforts and contributions made in this project.
</p>

## 🤝 Contributions
<p align="justify">
Contributions are the backbone of open-source projects! Fork our repository, apply your insights, and propose a pull request. Every bit of constructive feedback and enhancement is treasured.
</p>









