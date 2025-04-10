# 🧠 NLP & LLMs Notebook

## 📝 Notebook Overview
This notebook is made to explore how we can use **LLMs (Large Language Models)** and **NLP (Natural Language Processing)** to build smart tools. It uses both **open-source** and **paid AI models** to create **GenAI (Generative AI)** solutions for areas like **healthcare, business, finance,** and **human resources**.

## 📌 Notebook Implemented
- 🌐 A **website summarizer** that uses OpenAI and LLaMA to quickly give you the key points from any link.
- 🧾 A **smart brochure generator** powered by GPT or Ollama models (like LLaMA, Deepseek, Qwen, Mistral...) to create clean, AI-crafted content.
- 💡 A helpful **AI assistant** that explains tricky tech questions and code in a simple, structured way.  
- 🤖 A fun notebook where **GPT, Claude, and Deepseek** have hilarious and insightful conversations with distinct personalities.  
- 🌤️ A weather-aware **AI agent** that suggests fun activities and events based on where you are.  
- 🧪 A powerful tool for **generating synthetic datasets** —great for researchers, data scientists, and developers.  
- 🧠 A **smart internal assistant** built for Insurellm employees, using **RAG** to give fast, accurate answers to insurance-related questions.
- 📦 A complete price prediction pipeline using both traditional ML and frontier LLMs — with data curation, benchmarking, and fine-tuning.
    - 🧹 Part 1 – Data Curation & Preprocessing: Aggregate, clean, analyze, and balance product data to create high-quality train/test sets.
    - ⚔️ Part 2 – Model Benchmarking: Compare traditional ML (SVR, LR, XGBoost) with LLMs (GPT-4o, Claude, LLaMA, Deepseek...) and a human baseline.
    - 🔧 Part 3 – Fine-Tuning GPT-4o Mini: Train a smaller frontier model on the curated data and evaluate performance against zero-shot results.


## 🔑 Key Features
- Text and Document Processing
- Open-source / Closed-source Models
- Prompt Engineering
- Built-in Tools
- AI Assistant / AI Agent
- Gradio UI
- Advanced RAG Techniques
- Data Curation
- Fine Tune Frontier Models

## 📚 Prerequisites
- Software:
    - **Python 3.x**
    - **Jupyter Lab** / **Google Colab (GPU)**
    - **Anaconda** for environment management
    - **Ollama** for running local LLMs

- Skills:
    - Advanced knowledge of **LLMs (Large Language Models)**  
    - Familiarity with deep learning frameworks like **TensorFlow** and **PyTorch**  
    - Experience using **API-based LLMs**, such as the **OpenAI API** and **Hugging Face Transformers**  
    - Proficiency in **REST API integration**, including working with **endpoints** and tools like **Swagger**

	
## 📓 Notebook Overview
Each notebook starts with a friendly intro that helps you get up to speed quickly:
- 🎯 A short **description** of what the notebook does and **what it aims to solve** or demonstrate.

- 🧰 Clearly **listed LLMs** or **frameworks** involved (e.g., OpenAI, Hugging Face, Ollama, Deepseek...).

- 🔐 Any needed **API keys** or authentication steps (e.g., OpenAI, Hugging Face, etc.) are clearly indicated. If a **GPU is required** to run the notebook efficiently, it will also be specified.

- ⚙️ Key parameters you can **customize** are clearly listed to help you adapt the notebook to your specific needs.


## 🛠️ Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/lisek75/nlp_llms_notebook.git
    cd nlp_llms_notebook
    ```
2. Rename ``.the_secret_recipe`` to ``.env`` and add your API keys to unlock the magic! ✨🔑

3. Install the Conda Environment:
    ```sh
    conda env create -f environment.yml
    ```
    This will install all required dependencies inside the llms environment in your machine.

4. Activate the Environment
    ```sh
    conda activate llms
    ```
5. Run the Notebook
    ```sh
    jupyter lab
    ```


