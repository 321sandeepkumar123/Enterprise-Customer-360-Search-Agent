# Enterprise-Customer-360-Search-Agent
Enterprise Customer 360 Search Agent built using Azure AI Search, Azure AI Foundry, GPT-5 and Retrieval Augmented Generation (RAG). Implements vector search, semantic search, knowledge grounding, Azure Blob Storage, Managed Identity and RBAC for secure enterprise document retrieval.

An AI-powered Enterprise Customer Support Agent built using **Azure AI Foundry**, **Azure AI Search**, **GPT-5**, and **Retrieval Augmented Generation (RAG)**.

The solution enables users to search enterprise knowledge documents using natural language while providing accurate, grounded, and cited responses.

---

# 📌 Project Overview

Traditional chatbots rely on the LLM's pre-trained knowledge, which may produce outdated or hallucinated responses.

This project implements **Retrieval Augmented Generation (RAG)** to ensure responses are generated only from enterprise documents stored in Azure Blob Storage.

The agent retrieves the most relevant document chunks using Azure AI Search and GPT-5 generates an accurate answer grounded in enterprise knowledge.

---

# 🏗️ Architecture

```
                User Question
                      │
                      ▼
          Azure AI Foundry Agent
                      │
                      ▼
             Knowledge Base
                      │
                      ▼
            Azure AI Search
        (Vector + Semantic Search)
                      │
                      ▼
          Enterprise Documents
            (Azure Blob Storage)
                      │
                      ▼
                  GPT-5 Mini
                      │
                      ▼
      Grounded Answer with Citations
```

---

# 🔥 Features

- Enterprise AI Search
- Retrieval Augmented Generation (RAG)
- Vector Search
- Semantic Search
- Knowledge Base
- Azure Blob Storage Integration
- GPT-5 Mini
- AI Foundry Agent
- Enterprise Knowledge Grounding
- Source Citations
- Secure Authentication using Managed Identity
- Azure RBAC based access

---

# 🛠 Technologies Used

- Azure AI Foundry
- Azure AI Search
- Azure Blob Storage
- Azure OpenAI GPT-5 Mini
- Azure AI Foundry Knowledge Base
- Vector Embeddings
- Semantic Search
- Hybrid Retrieval
- Managed Identity
- Azure Role Based Access Control (RBAC)

---

# 📂 Enterprise Knowledge

The knowledge base is built from enterprise documents such as:

- Password Reset Procedure
- VPN Configuration Guide
- Customer Handbook
- Security Policies
- Enterprise Support Documentation
- Internal Knowledge Articles

---

# 🔍 How It Works

1. Enterprise documents are uploaded to Azure Blob Storage.
2. Azure AI Search indexes the documents.
3. Documents are chunked automatically.
4. Embeddings are generated.
5. Azure AI Search creates a Vector Index.
6. AI Foundry Knowledge Base connects to Azure AI Search.
7. User asks a question.
8. Relevant document chunks are retrieved.
9. GPT-5 generates a grounded response.
10. Source citations are included in the final answer.

---

# 🧠 AI Concepts Implemented

✅ Retrieval Augmented Generation (RAG)

✅ Vector Embeddings

✅ Vector Search

✅ Semantic Search

✅ Hybrid Search

✅ Document Chunking

✅ Knowledge Grounding

✅ GPT-5 Prompting

✅ Enterprise AI

✅ Azure Managed Identity

✅ Azure RBAC

---

# 🔐 Security

Instead of using API Keys, this solution uses:

- Azure Managed Identity
- Azure Role Based Access Control (RBAC)

The Azure AI Foundry Agent securely accesses Azure AI Search without storing credentials.

---


---

# 📈 Sample Query

**User**

```
How do I reset my password?
```

**Agent**

```
1. Go to the login page.
2. Click Forgot Password.
3. Enter your registered email.
4. Follow the reset email.
5. Create a new strong password.

Source:
Password Reset Procedure
```

---

# 🎯 Learning Outcomes

This project helped me gain hands-on experience with:

- Azure AI Foundry
- Azure AI Search
- GPT-5
- Retrieval Augmented Generation
- Enterprise Search
- Azure RBAC
- Managed Identity
- Vector Databases
- Knowledge Grounding
- Semantic Search

---

# 👨‍💻 Author

**Sandeep Kumar**

Software Engineer | Dynamics 365 CRM Developer | Azure AI Enthusiast

GitHub:
https://github.com/321sandeepkumar123

LinkedIn:
https://www.linkedin.com/in/kumarsandeep15

---

# ⭐ Future Enhancements

- Customer 360 Search across CRM records
- Dataverse Integration
- Multi-agent Architecture
- AI Evaluation
- Conversation Memory
- Citations with Confidence Score
- Enterprise Authentication with Microsoft Entra ID
