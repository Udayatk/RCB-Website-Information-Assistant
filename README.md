# RCB-Website-Information-Assistant
This Streamlit RAG chatbot answers questions using a Gemini LLM, powered by web data. It scrapes web pages (like RCB's), embeds content with Gemini text-embedding-004, and stores it in Pinecone ('uday' index). User queries are embedded, relevant info retrieved from Pinecone, then fed to Gemini gemini-2.0-flash-lite for answers.
