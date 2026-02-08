# 🚀 ChatGPT Prompt Engineering for Developers

---
## 📌 Overview

This repository contains **professional implementations, structured notes, and practical laboratory exercises** based on the course **ChatGPT Prompt Engineering for Developers** by **DeepLearning.AI** and **OpenAI**.

The project demonstrates how to effectively use **Large Language Models (LLMs)** programmatically to build reliable, scalable, and production-ready AI applications.

---

## 🎯 Learning Objectives

By exploring this repository, you will learn how to:

- Apply the **two fundamental principles** of high-quality prompt engineering  
- Implement an **iterative prompt development workflow**  
- Build automated systems for:
  - Text summarization  
  - Sentiment and inference analysis  
  - Content transformation  
  - Intelligent expansion and generation  
- Design and implement a **custom end-to-end chatbot** with system personas  

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Learning Objectives](#-learning-objectives)
- [Key Prompt Engineering Principles](#-key-prompt-engineering-principles)
- [Core Capabilities Implemented](#-core-capabilities-implemented)
- [Setup & Installation](#-setup--installation)
- [Environment Configuration](#-environment-configuration)
- [Project Structure](#-project-structure)
- [Production Best Practices](#-production-best-practices)
- [Acknowledgments](#-acknowledgments)
- [License](#-license)
- [Contributing](#-contributing)
- [Support](#-support)

---

## 💡 Key Prompt Engineering Principles

### 1️⃣ Write Clear and Specific Instructions

Best practices include:

- Use **delimiters** (`"""`, `---`, `< >`) to separate instructions from data  
- Request **structured outputs** such as JSON or HTML for system integration  
- Perform **conditional validation checks** before executing logic  
- Use **Few-Shot Prompting** with examples of successful outputs  

---

### 2️⃣ Give the Model Time to Think

Improve reasoning accuracy by:

- Breaking complex problems into **step-by-step instructions**  
- Asking the model to generate intermediate reasoning before final answers  
- Using structured reasoning workflows  

---

## 🛠 Core Capabilities Implemented

| Module | Description |
|---|---|
| **Summarizing** | Condenses text with constraints like word limits or topic focus |
| **Inferring** | Performs sentiment analysis, emotion detection, and topic classification |
| **Transforming** | Handles translation, tone conversion, and grammar correction |
| **Expanding** | Generates contextual and personalized content such as email responses |
| **Chatbot** | Implements an OrderBot with memory, context handling, and system prompts |

---

## ⚙️ Setup & Installation

### ✅ Prerequisites

- Python **3.8 or higher**  
- Valid **OpenAI API Key**  

Get your API Key here:  
👉 https://platform.openai.com/account/api-keys

---

### 📦 Install Dependencies

```bash
pip install openai python-dotenv
```

Or using the requirements file:

```bash
pip install -r requirements.txt
```

---

## 🔐 Environment Configuration

Create a `.env` file in the root directory:

```env
OPENAI_API_KEY=your_actual_api_key_here
```

⚠️ **Security Note:**  
Never commit your `.env` file or API keys to GitHub.

---

## 📂 Project Structure

```
├── 01_Guidelines/          # Principles of clear instructions
├── 02_Iterative/           # Prompt refinement workflows
├── 03_Summarizing/         # Text summarization implementations
├── 04_Inferring/           # Sentiment and inference models
├── 05_Transforming/        # Translation and format transformations
├── 06_Expanding/           # Content generation automation
├── 07_Chatbot/             # OrderBot chatbot implementation
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```

---

## 🚀 Production Best Practices

### 🎛 Temperature Selection
- `0.0` → Deterministic tasks (classification, logic, validation)  
- `0.7+` → Creative tasks (content generation, brainstorming)

---

### 🔒 Security
- Always use environment variables  
- Never hardcode API keys  
- Rotate keys periodically  

---

### ✅ Output Validation
- Validate JSON or structured outputs  
- Implement schema validation before processing LLM responses  

---

## 📚 Acknowledgments

Course content and inspiration from:

- **Isa Fulford — OpenAI**  
- **Andrew Ng — DeepLearning.AI**

🎓 Official Course:  
**ChatGPT Prompt Engineering for Developers**

---

## 📜 License

This project is for educational and learning purposes.  
Refer to course provider terms for content usage guidelines.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository  
2. Create a feature branch  
3. Submit a pull request  

---

## 📬 Support

If you have questions or suggestions, feel free to open an issue in the repository.

---

⭐ *Happy Prompt Engineering!*
