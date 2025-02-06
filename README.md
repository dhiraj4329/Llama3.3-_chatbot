# RAG - ChatBot: Retrieval Augmented Generation (RAG) chatbot using Llama3.3, Groq, Langchain, ChromaDB, and Streamlit
This RAG-ChatBot is a Python application that allows the user to chat with multiple PDF documents. You ask questions in natural language, in the same way as if you were to ask a human, and the application will provide relevant responses based on the content of the uploaded documents. This app uses Meta's Llama3.3 model to generate accurate answers to your questions, but the model will only answer questions that are about the uploaded documents. Here are some key points about the project:

Upload Documents: When the app is launched, you can upload a PDF document and chat with the document on the fly, no need to reload the app
Offline Documents: If you need to leave the app, when you come back, you won't need to upload the same document again, you can chat with it as soon as the app starts. Also, you can keep uploading documents to chat with all of them at the same time
The user interface was crafted with streamlit, with the goal of displaying all necessary information while being extremely simple. The user only has the "upload" button, all the rest is automated by the app
The model incorporates the chat history, retaining up to 10 users questions and model responses, so if you ask about something and want more details, you can just say "give me more details about that" and the model will know what you are reffering to
For each response, you can check the source in the sidebar, making sure that the model is not making up responses
