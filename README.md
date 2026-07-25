# 🚀 [Tips Hindawi](https://www.tipshindawi.com/) Challenge (June–July) 2026

> 🏆 This repository is my official submission for the [ **Tips Hindawi** ](https://www.tipshindawi.com/) **Challenge (June–July) 2026**.


## 👤 Participant
| Field            | Value                                |
| ---------------- | ------------------------------------ |
| Full Name        | Youssef Ahmed Hassan Fakhry          |
| Project Name     | Dynamic AI Interview Simulator       |
| GitHub Username  | yousef2a2fakhry-creator              |
| Challenge Batch  | June–July 2026                       |
| Training Program | Large Language Models (LLMs) Program |
| Organization     | [**Edrak for Ai**](https://edrak4ai.com/en)[cite: 4] |

---

# 📖 Project Overview

The Dynamic AI Interview Simulator is an interactive, GenAI-powered application designed to conduct realistic technical interviews. Using Retrieval-Augmented Generation (RAG), the system ingests a candidate's CV (PDF format) and extracts their specific technical skills, projects, and work experience. It then acts as an expert recruiter, dynamically generating tailored interview questions based on the candidate's background, and rigorously evaluating their responses to provide actionable feedback, a score out of 10, and key missing points.
---

# ✨ Features

* **Dynamic CV Analysis:** Utilizes PyPDFLoader and FAISS vector databases to index and retrieve specific, domain-agnostic context from candidate resumes.
* **Context-Aware Question Generation:** Reads the candidate's background to generate tailored, non-repetitive technical questions that reflect real-world recruitment scenarios.
* **Rigorous Structured Evaluation:** Employs LangChain's StructuredOutputParser to enforce strict JSON evaluation, scoring the candidate's answer and providing targeted improvement suggestions.
* **Stateful Interactive Loop:** Maintains conversational state during the interview to ensure the AI does not repeat previously asked questions.

---

# 🛠️ Technologies Used

* **Language & Frameworks:** Python, PyTorch
* **Large Language Model:** Mistral-Nemo-Instruct-2407 (via Hugging Face Transformers)
* **Orchestration & Output Parsing:** LangChain (`langchain_core`, `langchain_community`)
* **Retrieval-Augmented Generation (RAG):** FAISS (Vector Database), Sentence-Transformers (`all-MiniLM-L6-v2`)
* **Document Processing:** PyPDF
---

# ⚙️ Installation

1. Open the provided Jupyter Notebook in your preferred environment (e.g., local Jupyter Server, Kaggle, or Google Colab).
2. Run the dependency installation cell to set up the required Hugging Face and LangChain libraries.
3. Execute the setup cells to load the mistralai/Mistral-Nemo-Instruct-2407 LLM and the all-MiniLM-L6-v2 embedding model.

---

# 🚀 Usage

1. Place a target candidate CV (PDF) in the working directory and update the file path in the process_cv_to_context() function.
2. Run the execution simulation block to watch the AI generate a context-aware question, process a simulated user answer, and output the strict JSON evaluation.

---

# 📸 Demo
https://drive.google.com/drive/folders/1bNZDKoZtTuRxwngk0D5dxzVj-JinAuhE?usp=sharing
---

# 📈 Results

1. Successfully implemented a fully local, open-source RAG pipeline that processes CV documents dynamically.
2. Achieved strict JSON-formatted output from the Mistral model, enabling deterministic scoring and structured feedback extraction      without external API dependencies.
3. Maintained accurate conversational state to guarantee zero repetition of previously asked technical questions.

---

# 🔮 Future Improvements

1. Implement a speech-to-text (Whisper) and text-to-speech pipeline to upgrade the system into a fully voice-based interview experien
2. Develop a multi-agent interview panel featuring distinct AI roles to conduct advanced, high-pressure assessments for senior roles.
---

# 📚 About the Challenge

This project was developed as part of the [**Tips Hindawi**](https://www.tipshindawi.com/) **Challenge (June–July) 2026**.

[Tips Hindawi](https://www.tipshindawi.com/) is the internships department of [**Edrak for Ai**](https://edrak4ai.com/en), and the challenge encourages participants to build real-world projects, apply practical skills, and showcase their work through GitHub.

For more information about the challenge, training programs, and upcoming batches, visit the official [Tips Hindawi](https://www.tipshindawi.com/) website.

---

# 📄 License

This project is shared for educational and portfolio purposes.
