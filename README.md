# Chatbot-for-PDFs-using-NVIDIA-AI
This project is a Streamlit-based app that leverages NVIDIA’s NIM models to perform question answering over uploaded PDF documents. It uses LangChain components for document loading, splitting, embedding with NVIDIAEmbeddings, and storing vectors in a FAISS database. Users can input questions, and the app retrieves the most relevant document chunks to provide accurate, context-aware answers. The .env file securely holds the NVIDIA API key, and req.txt lists the required Python dependencies to set up the environment.
You can obtain a free API key by registering at NVIDIA Build.
Create a .env file in your project directory and add your NVIDIA API key as follows:
NVIDIA_API_KEY="your_api_key_here
