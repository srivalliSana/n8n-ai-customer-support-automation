
# AI-Powered Customer Support Automation (n8n)

## Overview
This project automates customer support email handling using n8n. Incoming emails are classified, relevant context is retrieved using a vector database, and AI-generated responses are sent automatically.

The workflow reduces manual email handling while ensuring contextual and accurate replies.

## Workflow Logic
1. Gmail Trigger listens for new incoming emails
2. Email content is cleaned and normalized
3. Rule-based logic identifies customer support queries
4. An AI Agent processes the query
5. Relevant knowledge is retrieved from Pinecone (RAG)
6. AI generates a response using Gemini
7. Reply is sent back via Gmail automatically

## Key Features
- Automated email triage
- AI-generated customer support responses
- Retrieval-Augmented Generation (Pinecone)
- Modular and reusable n8n workflow
- Secure credential handling (no secrets in repo)

## Tools & Technologies
- n8n
- Google Gmail API
- Google Gemini (LLM + Embeddings)
- Pinecone Vector Database

## How to Use
1. Clone the repository
2. Import the workflow JSON into n8n
3. Configure Gmail, Gemini, and Pinecone credentials
4. Activate the workflow

## Use Cases
- Startup customer support automation
- Email-based helpdesk workflows
- AI-assisted response systems

## Disclaimer
This workflow is intended for learning and prototyping purposes. Production usage may require additional validation, monitoring, and human review.
