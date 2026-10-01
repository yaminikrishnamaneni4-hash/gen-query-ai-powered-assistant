# gen-query-ai-powered-assistant
GenQuery-AI Powered Assistant – An AI-powered student assistant with RAG-based question answering, document processing, and intelligent conversation management.
# GenQuery-AI Powered Assistant

An AI-powered student assistant that uses Retrieval-Augmented Generation (RAG) to provide relevant and context-aware answers from uploaded documents.

## 📌 Project Overview

GenQuery-AI Powered Assistant is a full-stack AI application designed to help students interact with documents and obtain intelligent answers through an AI-powered chat interface.

The system combines an Angular/Ionic frontend with a Python Django backend and a RAG pipeline for document-based question answering.

## 🎯 Objectives

- Provide an AI-powered student assistant
- Allow users to upload documents
- Extract and process document content
- Retrieve relevant information using RAG
- Generate context-aware AI responses
- Manage user conversations
- Provide a simple and user-friendly interface

## ✨ Key Features

- 🔐 User Registration and Login
- 💬 AI Chat Interface
- 📄 Document Upload
- 🔎 RAG-Based Question Answering
- 🧠 Context-Aware AI Responses
- 🗂️ Conversation Management
- 📚 Document-Based Information Retrieval
- 📱 Angular/Ionic User Interface

## 🛠️ Technologies Used

### Frontend

- Angular
- Ionic
- TypeScript
- HTML
- SCSS

### Backend

- Python
- Django
- Django REST Framework

### AI / RAG

- Retrieval-Augmented Generation (RAG)
- Text Embeddings
- Vector Store
- Large Language Model (LLM)
- Document Processing

## 🏗️ System Architecture

```text
                    User
                      |
                      v
             Angular / Ionic
                  Frontend
                      |
                      v
              Django REST API
                      |
                      v
            Document Processing
                      |
                      v
                RAG Pipeline
                      |
        +-------------+-------------+
        |             |             |
        v             v             v
   Extraction     Chunking      Embeddings
                                      |
                                      v
                               Vector Store
                                      |
                                      v
                             Relevant Context
                                      |
                                      v
                              Large Language
                                  Model
                                      |
                                      v
                              AI Response
                                      |
                                      v
                                    User
