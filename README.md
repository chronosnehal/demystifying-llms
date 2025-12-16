# Demystifying LLMs: Interactive Notebook Suite

This repository contains modular Jupyter notebooks based on the whitepaper "Demystifying Large Language Models" authored by Snehal Bhasakhetre.

## 📂 Structure
```plaintext
demystifying-llms/
├── notebooks/
│   ├── 1_Introduction_to_LLMs.ipynb
│   ├── 2_How_LLMs_Are_Trained.ipynb
│   ├── 3_LLM_Architectures.ipynb
│   ├── 4_LLM_Training_vs_Inference.ipynb
│   ├── 5_Prompt_Engineering_and_LLM_Optimization.ipynb
│   ├── 6_Evaluation_and_Metrics_for_LLMs.ipynb
│   ├── 7_Ethical_Considerations_and_Bias_in_LLMs.ipynb
│   ├── 8_Fine_Tuning_and_Adaptation_of_LLMs.ipynb
│   ├── 9_LLM_Deployment_and_Scaling.ipynb
│   ├── 10_Future_of_LLMs_and_Emerging_Trends.ipynb
│   └── utils_llm_connector.ipynb   👈 reusable LLM connector
├── whitepaper/
│   └── Demystifying LLMs.pdf
├── requirements.in
├── requirements.txt
└── README.md
```

- `notebooks/`: Section-wise notebooks and reusable utilities
- `utils_llm_connector.ipynb`: Handles dynamic LLM connections (OpenAI/Azure OpenAI)
- `whitepaper/`: Source and PDF of the whitepaper
- `requirements.txt`/`requirements.in`: Python dependencies
- `README.md`: Project documentation

## 🚀 Setup
1. Install Python 3.12
2. Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate
3. Install dependencies:
   pip install -r requirements.txt

## 📑 Usage
- Open JupyterLab or Notebook
- Run `utils_llm_connector.ipynb` first to configure LLM provider
- Import LLMConnector in other notebooks as shown

## 🔑 API Keys
- Create `.env` file for API keys: