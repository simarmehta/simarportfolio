#  Menu-RAG

Engineered a Retrieval-Augmented Generation (RAG) chatbot application designed to provide users with detailed information about restaurant menus by integrating structured internal data with external cuisine-related content. The system consists of three main components: a data ingestion and indexing module that processes internal CSV data and external web content, converting text into embeddings using SentenceTransformer and building vector indexes with FAISS; a chatbot backend built with FastAPI, which receives user queries, retrieves relevant records, applies deduplication and classification, assembles prompts with conversation history, and generates responses using GPT-4; and a Gradio-based frontend that provides an interactive chat interface, maintaining conversation context and displaying relevant information. This project demonstrates the effective use of RAG techniques in enhancing user interactions with restaurant menu data.
<br>

**[<i class="fa-solid fa-up-right-from-square"></i> Uncover the Project - Click Here](https://github.com/simarmehta/RAG-MenuData)**
