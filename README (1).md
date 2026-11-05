# AI Placement Preparation Assistant 🎯

An AI-powered interview preparation application built using **LangChain, OpenRouter, and Streamlit**.

## Features

- Role-based interview preparation
- Experience-level selection
- Custom difficulty selection
- AI-generated interview questions
- Model answers and explanations
- Structured output using Pydantic

## Tech Stack

- Python
- LangChain
- OpenRouter
- Pydantic
- Streamlit

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/ManojgowdaBY/AI-Placement-Preparation-Assistant.git
cd AI-Placement-Preparation-Assistant
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**

```powershell
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure environment variables

Create a `.env` file in the project directory:

```env
OPENROUTER_API_KEY=your_openrouter_api_key
MODEL_NAME=openai/gpt-4o-mini
```

Replace the placeholder with your actual OpenRouter API key.

### 6. Run the application

```bash
streamlit run app.py
```

## Project Structure

```text
AI-Placement-Preparation-Assistant/
│
├── app.py
├── generator.py
├── prompts.py
├── schemas.py
├── requirements.txt
├── .env
└── .gitignore
```

## Author

**Manoj Gowda B Y**

GitHub: [ManojgowdaBY](https://github.com/ManojgowdaBY)