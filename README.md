# 🧠 Local RAG with LLaMA.cpp

This project builds a simple Retrieval-Augmented Generation (RAG) pipeline using a local LLaMA GGUF model (`llama-cpp`), FAISS for vector search, and a PDF document for contextual grounding.

## 🚀 Setup & Usage

1. Clone the repository
2. Download the requisite GGUF file from:
   https://huggingface.co/bartowski/Dolphin3.0-Llama3.2-3B-GGUF/blob/main/Dolphin3.0-Llama3.2-3B-Q5_K_M.gguf
   or choose your own GGUF
   Update model_path accordingly
3. Download the document from:
   https://www.pdfdrive.com/you-are-your-own-gym-the-bible-of-bodyweight-exercises-for-men-and-women-d157018247.html
   or choose your own document
   Update path accordingly
4. Ensure all files are in the same directory
5. use `pip install -r requirements.txt` to install dependencies
6. Run the notebook 
