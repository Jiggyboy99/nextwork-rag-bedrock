🤖 Retrieval-Augmented Generation (RAG) Chatbot using Amazon Bedrock

A Retrieval-Augmented Generation (RAG) powered chatbot built with **Amazon Bedrock**, **OpenSearch Serverless**, and **Amazon S3** — capable of answering questions based on **your own data and documents**.

This project was built as part of the **NextWork Cloud + AI Challenge**, showcasing how **AWS Bedrock foundation models (Llama & Titan)** can be integrated with **retrieval-based AI** to create intelligent, data-driven chatbots.

---

🚀 Features

✅ Upload documents to your Amazon S3 bucket
✅ Automatically index and store embeddings in Amazon OpenSearch Serverless 
✅ Retrieve relevant context dynamically using RAG architecture 
✅ Generate human-like responses using **Amazon Bedrock foundation models (Llama/Titan)
✅ Simple, interactive chatbot UI built with **Streamlit / Flask  
✅ Scalable, secure, and production-ready AWS integration  


 🧠 System Architecture Overview

This project follows a **Retrieval-Augmented Generation (RAG)** workflow:

1. Documents are uploaded to Amazon S3  
2. Data is embedded and indexed in **OpenSearch Serverless**.  
3. When a user enters a query, the chatbot retrieves relevant context from the knowledge base.  
4. Context is passed into **Amazon Bedrock** (Llama or Titan models).  
5. A final, natural language response is generated and displayed on the chatbot UI.

![RAG Architecture Diagram](./architecture.png)
https://drive.google.com/file/d/1wVOvjO8hb6QGm9-xKuYO8VxGF9QQU-ac/view?usp=sharing


---
   🧩 Tech Stack

🧩 Core Technologies
- Amazon Bedrock** – foundation models for knowledge-based Q&A  
- Amazon S3** – stores and manages uploaded document data  
- Amazon OpenSearch Serverless** – vector store for embeddings and semantic search  
- Python (Boto3 SDK)** – connects and orchestrates AWS services  
- Streamlit / Flask** – builds the user-facing chatbot interface  

🤖 AI & NLP
- Retrieval-Augmented Generation (RAG)** – blends document retrieval with generative AI  
- Llama & Titan Foundation Models** – generate intelligent, context-aware answers  
- Embeddings + Semantic Search** – improves context relevance  

⚙️ Infrastructure & Deployment
- AWS IAM** – secure role-based access  
- Amazon CloudWatch – monitors and logs operations  
- AWS CLI / SDK (Boto3) – programmatic access to AWS resources  

🧰 Developer Tools
- Python 3.10+**  
- Git & GitHub** – version control and collaboration  
   


⚙️ Setup & Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/aws-rag-chatbot.git
cd aws-rag-chatbot

