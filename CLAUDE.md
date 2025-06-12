# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **LLM Cookbook Japan** (llm-cookbook_jp) project - a comprehensive Japanese language handbook for developers learning Large Language Models. The project is based on Andrew Ng's LLM course series, translated and adapted for Japanese learners. It covers the complete workflow from Prompt Engineering to RAG development and model fine-tuning.

## Repository Structure

The repository is organized into three main directories:

- **content/**: Bilingual code and executable Jupyter notebooks (most frequently updated)
- **docs/**: Online readable Markdown tutorials for required courses 
- **figures/**: Image and diagram files
- **utils/**: Shared utility modules for model loading and chat functionality

### Course Organization

**Required Courses (必修):**
1. Prompt Engineering For Developers
2. Building Systems with the ChatGPT API  
3. LangChain for LLM Application Development
4. LangChain Chat with Your Data

**Elective Courses (選修):**
- Advanced Prompting
- Advanced Retrieval for AI with Chroma
- Building Generative AI Applications with Gradio
- Building and Evaluating Advanced RAG Applications
- Evaluating and Debugging Generative AI
- Finetuning Large Language Models
- Functions, Tools and Agents with LangChain
- Large Language Models with Semantic Search

## Development Commands

### Environment Setup
```bash
# Install UV package manager
pip install uv
set UV_INDEX=https://mirrors.aliyun.com/pypi/simple

# Install dependencies 
uv sync --python 3.12 --all-extras

# Activate virtual environment (Windows)
cd .venv/Scripts
activate

# Start Jupyter notebook
jupyter notebook
```

### API Configuration
Create a `.env` file in the project root:
```text
API_KEY=your_api_key
BASE_URL=model_base_url
```

## Key Architecture Components

### Model Integration
- Uses OpenAI-compatible API through SiliconFlow (https://api.siliconflow.cn/v1)
- Centralized model loading in `utils/` directory
- Support for multiple model endpoints (Qwen, ChatGLM, etc.)
- Environment-based configuration with dotenv

### Utility Modules
- `utils/text2text_chat.py`: Text generation model integration
- `utils/langchain_chat.py`: LangChain integration utilities  
- `utils/image2text_chat.py`: Multimodal model support
- `utils/embedding_load_model.py`: Embedding model loading

### Course-Specific Requirements
Some courses have individual `requirements.txt` files:
- LangChain courses: Additional LangChain dependencies
- RAG courses: Vector database and retrieval dependencies
- Fine-tuning courses: Model training dependencies

## Working with Notebooks

### Model Loading Pattern
All notebooks use this standard pattern for API initialization:
```python
import os
from dotenv import load_dotenv, find_dotenv

loaded = load_dotenv(find_dotenv(), override=True)
API_KEY = os.getenv("API_KEY")
BASE_URL = "https://api.siliconflow.cn/v1"
```

### Course Dependencies
Check for course-specific requirements before running notebooks:
- Navigate to specific course directory
- Install additional requirements if present: `pip install -r requirements.txt`

## Technical Requirements

- **Python**: 3.12+ (strict requirement)
- **Package Manager**: UV (preferred) or pip
- **API Access**: OpenAI-compatible API key required
- **Environment**: Jupyter Notebook support essential

## Important Notes

- All content is bilingual (Japanese/Chinese) with focus on Japanese learners
- Project uses Chinese mirrors for package installation (Tsinghua/Aliyun)
- Each course directory is self-contained with its own data and utilities
- Documentation is generated from content/ to docs/ for online viewing