<h1 align="center">Biplob Sinha</h1>
<h3 align="center">AI Product Architect · LLMs, RAG &amp; Generative AI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/biplob-sinha-a10635172/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

### About me

AI Product Architect working on LLM and generative-AI applications. The projects below show the kind of work I do: grounded, source-cited AI assistants, data dashboards and production-style ML pipelines.

### What I work on

- **LLMs, RAG & Generative AI:** retrieval-augmented generation, vector search, prompt design and guardrails against made-up answers
- **Evaluation:** measuring groundedness and relevance with LLM-as-a-judge, so improvements are proven rather than assumed
- **Credit risk modelling:** bank-style application scorecards (WoE/IV, logistic regression, points scaling) with a full validation pack: Gini, KS, PSI and calibration
- **Data & analytics:** turning raw transaction data into dashboards that support decisions
- **Product & architecture:** writing PRDs, defining scope and success metrics, and designing AI systems end to end

### Featured projects

**LLMs, RAG & Generative AI**

| Project | What it does | Stack |
| --- | --- | --- |
| [**medical-rag-assistant**](https://github.com/bks1984/medical-rag-assistant) | Clinical Q&A assistant over the 4,000-page Merck Manual. Answers only from retrieved excerpts and cites chapter and page. In an LLM-as-a-judge evaluation, RAG scored 5.0/5 for groundedness, against 1.75 for a plain LLM. | Python · LangChain · ChromaDB · Groq (gpt-oss-120b) / OpenAI · sentence-transformers · Streamlit |
| [**llm-research-assistant**](https://github.com/bks1984/llm-research-assistant) | Upload long research PDFs and ask questions in plain English. Answers cite file and page, and the app also extracts paper metadata and summaries, finds trends across papers, and compares RAG with a plain LLM. | Python · LangChain · ChromaDB · Groq / OpenAI · Streamlit · Docker |
| [**rag-telecom-chatbot**](https://github.com/bks1984/rag-telecom-chatbot) | Self-serve support assistant that answers Tier-1 telecom questions only from an FAQ, resolved tickets and PDF guides, cites its sources, and escalates when it can't answer confidently. | Python · LangChain · ChromaDB · Groq (Qwen) · Streamlit |

**Credit Risk Modelling**

| Project | What it does | Stack |
| --- | --- | --- |
| [**credit-scorecard-give-me-some-credit**](https://github.com/bks1984/credit-scorecard-give-me-some-credit) | Points-based application scorecard on Kaggle's *Give Me Some Credit* (150k borrowers) that predicts 90+ days delinquency. Monotonic WoE binning, IV-based selection and sign-constrained logistic regression, scaled to 600 points at 50:1 odds with 20 points to double the odds (PDO 20). Holdout Gini 0.70, KS 0.55, PSI ≈ 0. Ships with score-band calibration, a cut-off strategy and a deployable JSON scorecard. | Python · pandas · scikit-learn · matplotlib · pytest · GitHub Actions |

**Data & MLOps**

| Project | What it does | Stack |
| --- | --- | --- |
| [**credit-card-fraud-dashboard**](https://github.com/bks1984/credit-card-fraud-dashboard) · [live demo](https://bks1984.github.io/credit-card-fraud-dashboard/) | Interactive dashboard over 284,807 card transactions: fraud rate, value at risk, hourly spikes, riskiest amount bands and the strongest fraud signals, with click-to-filter. | Python · d3.js · GitHub Pages |
| [**MLOps_pipelines**](https://github.com/bks1984/MLOps_pipelines) | End-to-end MLOps pipeline for a diabetes-risk classifier: data registration, training and Docker deployment, automated with GitHub Actions. | Python · scikit-learn · Docker · GitHub Actions |

### Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square" alt="ChromaDB"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" alt="Groq"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3dotjs&logoColor=white" alt="D3.js"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
</p>

---

<p align="center"><i>Open to conversations about AI product design and LLM applications. The best way to reach me is <a href="https://www.linkedin.com/in/biplob-sinha-a10635172/">LinkedIn</a>.</i></p>
