<h1 align="center">Abdul Mohammad</h1>

<p align="center">
  <strong>AI Safety Researcher · Research Engineer · UC Berkeley</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdul-mohammad-344320315/">
    <img src="https://img.shields.io/badge/LinkedIn-003262?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:abdulmohammad@berkeley.edu">
    <img src="https://img.shields.io/badge/Email-FDB515?style=for-the-badge&logo=gmail&logoColor=003262" alt="Email">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI_Safety-003262?style=flat-square" alt="AI Safety">
  <img src="https://img.shields.io/badge/LLM_Evaluation-003262?style=flat-square" alt="LLM Evaluation">
  <img src="https://img.shields.io/badge/Reliable_Agents-003262?style=flat-square" alt="Reliable Agents">
</p>

I'm a UC Berkeley student studying **Applied Mathematics, Data Science, and Computer Science**. I build evaluation systems for language models and tool-using agents, with a focus on whether safety behavior survives deployment pressure.

> **My focus:** the gap between an AI system that looks safe on average and one whose individual decisions remain dependable under real-world constraints.

## 🔭 What I'm Working On

- **Avocado** *(private research collaboration)* — leading the durability track, testing corrigibility and jailbreak durability in fine-tuned LLMs.
- **[Safety Invariance](https://github.com/abdulm5/safety-invariance)** — measuring whether FP16, INT8, and NF4 quantization preserve the safety decisions of tool-using agents.

## 📄 Recent Highlight

I presented first-authored research at Stanford's **[PAI26 Conference](https://datascience.stanford.edu/pai26-poster-sessions#session2)** on the epistemic safety of AI-generated physics explanations.

The pilot study found that AI explanations matched human explanations on correctness, while showing lower completeness and less intuition-bridging content. **[View the research, paper, and poster →](https://github.com/abdulm5/physics-explanation-safety)**

## 🚀 Selected Work

| Project | Stack | Result |
| --- | --- | --- |
| **[Safety Invariance](https://github.com/abdulm5/safety-invariance)** | Python, PyTorch, Hugging Face, CUDA | Built a one-GPU agent evaluation framework. Across 2,065 matched Qwen2.5-3B cases, aggregate security barely changed after NF4 quantization, but **73 individual security decisions flipped**. |
| **[Epistemic Safety in AI Physics Tutors](https://github.com/abdulm5/physics-explanation-safety)** | Python, NLP, statistical analysis | Studied 60 explanations across 20 physics prompts. AI and human answers had equal median correctness, but AI explanations had lower completeness and intuition coverage. |
| **[PagerAgent](https://github.com/abdulm5/paperAgent)** | FastAPI, PostgreSQL, Redis, React | Built an evidence-grounded incident-response copilot that produced incident briefs in **under 30 seconds** and reduced manual triage and reporting effort by **70%** in simulated outages. |
| **[OctagonRank](https://github.com/abdulm5/OctagonRank)** | Node.js, Cheerio, React | Built a UFC ranking engine from **8,500+ fights**, **2,500+ fighters**, and **40,000+ round-level records**, using 50+ features to surface trends beyond win-loss records. |

<details>
<summary><strong>🧪 Research Details</strong></summary>

### Behavioral Safety Invariance Under One-GPU Quantization

**Role:** First author. I designed and built the evaluation pipeline for FP16, INT8, and NF4 models using native agent benchmarks.

**Finding:** On a controlled 65-case subset, the FP16-to-NF4 security flip rate was **36.9%**, compared with a **7.7%** FP16 self-repeat noise floor. Aggregate scores alone can hide meaningful behavioral changes.

### Epistemic Safety in AI Physics Tutors

**Role:** First author. I created the study, annotation framework, analysis pipeline, paper, and conference poster.

**Finding:** Human and AI explanations received the same median correctness rating, but AI explanations had lower median completeness (**4.0 vs. 5.0**) and intuition-bridging coverage (**20% vs. 35%**).

</details>

## 💻 Tech Stack

### Languages

![Python](https://img.shields.io/badge/PYTHON-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000)
![Swift](https://img.shields.io/badge/SWIFT-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### AI & Data

![PyTorch](https://img.shields.io/badge/PYTORCH-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HUGGING_FACE-FFD21E?style=for-the-badge&logo=huggingface&logoColor=000000)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![NumPy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-8A2BE2?style=for-the-badge)

### Backend & Applications

![FastAPI](https://img.shields.io/badge/FASTAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/POSTGRESQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/REDIS-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Node.js](https://img.shields.io/badge/NODE.JS-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/REACT-61DAFB?style=for-the-badge&logo=react&logoColor=000000)
![REST APIs](https://img.shields.io/badge/REST_APIS-6DB33F?style=for-the-badge&logo=fastapi&logoColor=white)

### Infrastructure & Tools

![Docker](https://img.shields.io/badge/DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/LINUX-FCC624?style=for-the-badge&logo=linux&logoColor=000000)

## 🤝 Let's Connect

I'm interested in collaborating on **AI safety evaluation, reliable agents, and research engineering**.

📫 **[abdulmohammad@berkeley.edu](mailto:abdulmohammad@berkeley.edu)** · **[LinkedIn](https://www.linkedin.com/in/abdul-mohammad-344320315/)**
