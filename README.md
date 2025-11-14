# File-Q-Na
File Q/NA AI reads an uploaded document, splits it into text chunks, and creates embeddings using FAISS. When a user asks a question, it finds the most relevant parts of the file. The AI model then generates an accurate answer based only on the document.

Features
Upload and read documents (PDF / DOCX / TXT)
Automatically split the document into text chunks
Generate embeddings using Sentence-Transformers
Store vectors using FAISS for fast search
Retrieve relevant text from the document
Generate answers using FLAN-T5 model

Technologies Used
Python
Google Colab
LangChain
FAISS
Sentence-Transformers
Transformers (HuggingFace)
FLAN-T5 Model
