# smart-medical-assistant
AI-powered PDF medical report assistant using Transformers and Gradio

#  Smart Medical Assistant

A smart AI-powered assistant that helps you understand medical reports easily.  
Just upload a medical PDF report, ask your question, and get accurate answers directly from the report content.

##  Project Idea  
Many people—especially older adults—receive medical reports but find the terms and details confusing.  
This assistant allows users to ask questions like "What is the diagnosis?" or "What is the treatment?" and get answers without having to visit the doctor repeatedly.

##  Tools & Technologies Used

- **PyMuPDF (fitz)**: To extract text from PDF files.  
- **SentenceTransformer (all-MiniLM-L6-v2)**: To convert text into numerical embeddings.  
- **Transformers (roberta-base-squad2)**: For question answering.  
- **FAISS**: To search and find the most relevant text chunks.  
- **Gradio**: To build a simple, interactive web interface.  
- **Google Colab**: For easy development and sharing.

##  How to Run  
1. Open the project on Google Colab.  
2. Upload and run the `app.py` script.  
3. The Gradio interface will launch, letting you upload a PDF and ask questions.


---

