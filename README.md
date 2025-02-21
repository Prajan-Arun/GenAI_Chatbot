AI-Powered Article Researcher:

This repository contains the code for an AI-powered chatbot that can answer questions based on articles you provide. It's built using LangChain, Streamlit, OpenAI, and FAISS.

Features:

Analyze multiple articles: Feed the chatbot URLs of articles you want to research (up to 3 at a time, but can be scaled).
Ask questions in natural language: Get answers to your questions based on the content of the articles.
Targeted information retrieval: Focuses on the specific articles you provide, ensuring relevant and accurate answers.
Organized research: Keeps track of the articles you've analyzed and the questions you've asked.
User-friendly interface: Built with Streamlit for easy interaction.

How to run:

Clone the repository: git clone https://github.com/Prajan-Arun/GenAI_Chatbot.git
Install dependencies: pip install -r requirements.txt
Set up your OpenAI API key: Create a file named ApiKey.py and add your API key: openapi_key = "YOUR_ACTUAL_OPENAI_API_KEY" 
Run the Streamlit app: streamlit run Main.py

How it works:

Load articles: Provide URLs of the articles you want to analyze.
Process and embed: The application uses LangChain to load and process the articles and OpenAI to generate embeddings that capture the meaning of the text.
Build a knowledge base: FAISS is used to create a searchable index of the embedded information.
Ask questions: Type your questions in natural language.
Get answers: The chatbot retrieves relevant information from the articles and provides concise answers.
Technologies used
LangChain: For loading, processing, and managing the articles.
Streamlit: For building the user interface.
OpenAI API: For generating text embeddings.
FAISS: For efficient similarity search and information retrieval.

Project Status:

This project is currently complete.

Future Enhancements:

Expand URL capacity: Allow for more articles to be analyzed at once.
Support different document formats: Enable uploading and analyzing documents in formats like PDF.
Improve user interface: Enhance the design and functionality of the Streamlit app.
Add more advanced features: Explore features like summarization, topic extraction, and sentiment analysis.
