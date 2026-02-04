---
layout: "default"
title: "🌐 openweb_rag - Easy Document Chat with OpenAI"
description: "📄 Explore Open WebUI with OpenAI API for chat and document Q&A, featuring seamless PDF support and persistent storage in a complete Docker setup."
---
# 🌐 openweb_rag - Easy Document Chat with OpenAI

## 🚀 Getting Started
Welcome to Open WebUI with OpenAI API and RAG! This guide will help you download and run the application smoothly.

## 📥 Download
[![Download openweb_rag](https://img.shields.io/badge/download-openweb_rag-blue)](https://github.com/Panada7w7/openweb_rag/releases)

## 🛠️ Prerequisites
Before you begin, ensure you have the following tools set up.

### 1. Docker & Docker Compose
- **Docker**: Install Docker Desktop for macOS or Windows. For Linux, use Docker Engine.
- **Docker Compose**: Version must be 3.8 or higher.
- **Verify Installation**: Run these commands in your terminal:
  ```bash
  docker --version
  docker compose version
  ```

### 2. OpenAI API Key
You will need an OpenAI API key to use this application:
- Sign up at [OpenAI Platform](https://platform.openai.com/).
- Create your API key at [API Keys](https://platform.openai.com/api-keys).
- Make sure to enable credits or billing for your account.

### 3. System Requirements
- **Minimum**: 2 GB of RAM.

## ⚙️ Installation Steps
Follow these steps to set up and run the application.

### 1. Download the Latest Release
Visit the following link to get the latest version of openweb_rag:  
[Download from the Releases Page](https://github.com/Panada7w7/openweb_rag/releases)

### 2. Extract the Files
Once the download is complete, extract the files from the downloaded archive.

### 3. Open a Terminal
Navigate to the folder where you extracted the files using your terminal application.

### 4. Setting Up Environment Variables
You need to set the OpenAI API key in your environment. Use the following command to set it:
```bash
export OPENAI_API_KEY="your_openai_api_key"
```
Replace `"your_openai_api_key"` with your actual key.

### 5. Run the Application
To start the application, run this command in your terminal:
```bash
docker-compose up
```
This command will initialize all necessary services.

### 6. Access the Application
Open your web browser and go to:
```
http://localhost:8080
```
You will see the Open WebUI interface.

## 📑 Features
Here’s what you can do with openweb_rag:

- **OpenAI Integration**: Utilize GPT-4o, GPT-4 Turbo, or other OpenAI chat models.
- **RAG and Document Q&A**: Upload PDF documents, create knowledge bases, and chat with your files.
- **Persistent Storage**: All your chat histories, uploads, and embeddings are saved and will not disappear when you restart the container.
- **No Local LLMs**: You don’t need to worry about local models; this application uses only the OpenAI API.
- **Built-in Vector Database**: Open WebUI comes with ChromaDB to manage your embeddings.

## 🔧 Troubleshooting
If you face issues during installation or running the application, consider the following:

### Common Issues
- **Docker Not Running**: Ensure that Docker is active before running any commands.
- **Incorrect API Key**: Double-check that your OpenAI API key is correctly set.

### Logs
You can check the terminal for logs to debug issues. Please ensure Docker is running properly.

## 🎉 Support
For further assistance, feel free to open an issue on the GitHub page or contact our support team. We’re here to help.

## 🔗 Additional Resources
- [OpenAI Documentation](https://platform.openai.com/docs/)
- [Docker Documentation](https://docs.docker.com/)

## 📥 Download Again
Don’t forget to download the latest version of openweb_rag here:  
[Download from the Releases Page](https://github.com/Panada7w7/openweb_rag/releases)