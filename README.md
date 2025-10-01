# Quiz-Generator

# 📘 Study For a Quiz – Quiz Generator

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyPDF2](https://img.shields.io/badge/PyPDF2-3.0.0-green)
![python-docx](https://img.shields.io/badge/python--docx-1.0.0-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

Automatically generate multiple-choice quizzes from study materials (TXT, PDF, DOCX). Supports both **OpenAI API-based smart questions** and **Offline simple questions** for learning and testing purposes.

</div>

---

## 📊 Project Overview

Study For a Quiz – Quiz Generator is a Python-based project that helps students **create quizzes automatically** from study files. The workflow supports multiple file formats and provides two modes:

1. 🟢  **API Version (Online)**: Uses OpenAI API to generate high-quality questions .
2. 🔵 **Offline Version**: Generates simple random questions without requiring an API key.

This project is designed for learning, revision, and self-assessment.

---

---
## 🚀 Key Features

| Feature | Description |
|---------|-------------|
| 📄 **File Upload** | Supports **TXT, PDF, and DOCX** files |
| 🎯 **Custom Quiz Size** | Generate **10, 20, or 30 questions** per session |
| 🧠 **Multiple-choice Format** | Questions with **4 options (A, B, C, D)** and correct answers |
| 🌐 **Two Modes** | **Online (API)** for smart questions / **Offline** for simple questions |
| 💻 **Cross-platform Compatibility** | Works on **VS Code**, **Jupyter Notebook**, and **Google Colab** |

---
## 🖥️ Flowchart (Mindmap)

```mermaid
graph TD
    A[Upload File] --> B{Choose Mode}
    B --> C[Online (API)]
    B --> D[Offline]
    C --> E[Generate Questions]
    D --> E
    E --> F[Display Quiz Output]
    F --> G[Save / Copy / Practice]

---
## 🗂️ Project Structure

```
📁 quiz-generator
 ┣ 📜 study_buddy_api.py        # Online version using OpenAI API
 ┣ 📜 study_buddy_offline.py    # Offline version without API
 ┣ 📜 requirements.txt          # Project dependencies
 ┗ 📜 README.md                 # Project documentation
```

> This is the complete structure of the project.
>
> * `study_buddy_api.py`: Runs the quiz generator using OpenAI API (online mode).
> * `study_buddy_offline.py`: Runs the quiz generator offline without needing an API key.
> * `requirements.txt`: Lists all Python dependencies required to run the project.
> * `README.md`: Documentation and instructions for installation and usage.

---

## ⚙️ Installation & Setup

### Prerequisites

* Python 3.8+
* pip package manager

### 1. Clone the Repository

```bash
git clone https://github.com/ayaeslam294/quiz-generator.git
cd quiz-generator
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### ▶️ Running on VS Code / Terminal

```bash
python study_buddy_api.py     # Online version (requires OpenAI API key)
python study_buddy_offline.py # Offline version
```

1. Upload your file (TXT, PDF, or DOCX) when prompted.
2. Enter the number of questions (10, 20, or 30).
3. The quiz will be displayed in the console.

---

### ▶️ Using Jupyter Notebook / JupyterLab

1. Open the notebook in JupyterLab.
2. Run cells step by step.
3. Upload your study file and choose the number of questions.

---

### ▶️ Using Google Colab

1. Upload the notebook to Google Colab.
2. **Online Version:** Store your `OPENAI_API_KEY` in Colab Secrets.
3. **Offline Version:** No API key required.
4. Run the notebook cells and interact with the quiz generator.

---

## 📝 Example Output

```
=== Quiz ===

Q1. What is the first word in the following sentence from the study material?
A) Data
B) Python
C) Analysis
D) Science
Answer: Python
```

> The offline mode generates simple questions based on the text, while the API mode generates more intelligent questions.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 🙏 Acknowledgments

* [OpenAI](https://openai.com/) for the GPT models.
* [PyPDF2](https://pypi.org/project/PyPDF2/) for reading PDF files.
* [python-docx](https://python-docx.readthedocs.io/) for reading DOCX files.
* [Google Colab](https://colab.research.google.com/) for notebook support.

---

## 📞 Contact

For questions or suggestions, please open an issue or contact:
**Aya Eslam Elsawy**
[LinkedIn](https://www.linkedin.com/in/aya-eslam-1b8792349) | [GitHub](https://github.com/ayaeslam294)


تحبي أعملها؟
