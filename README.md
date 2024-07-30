# MedEase-AI

## Introduction

The MedEase-AI project leverages AI to enhance patient interactions by providing relevant information from medical data. This project demonstrates the intersection of medicine and AI, aiming to improve the efficiency and accuracy of medical information retrieval.

## Features

- **Content Extraction:** Integrates a PDF file containing medical data for effective content extraction and processing.
- **Semantic Search:** Implements semantic search capabilities to retrieve relevant information from embeddings.
- **Library Version Management:** Emphasizes the importance of specifying library versions to prevent upgrade-related errors.
- **Future Enhancements:** Plans include Docker integration and front-end interface development.

## Tech Stack

- **Language:** Python
- **Libraries/Frameworks:** Langchain, Flask
- **Vector Storage:** Pinecone

## Creating a Project Template

- Automate folder and file creation using a template file (`template.pipe`).
- Manage file paths and directories with Python libraries (`os`, `path`).
- Log the creation process for tracking.

## Modular Coding

- Convert notebook experiments into modular code.
- Develop a project architecture with separate helper files and directories.
- Write functions for text splitting and other necessary tasks.

## Vector Database Integration

- Load the PDF and extract text.
- Download models from Hugging Face.
- Initialize Pinecone and store vectors in the database.

## Web Application Development

- Set up a Flask application.
- Create routes and integrate HTML templates using Bootstrap.
- Handle user inputs and generate responses using the QA bot.

## Final Steps

- Ensure the chatbot can handle normal messages using a pretrained language model.
- Demonstrate the use of the project template for other applications, such as a finance-related chatbot.

## Contributing

If you wish to contribute to this project:

- Fork the repository.
- Create a new branch for your changes.
- Submit a pull request with a detailed description of your modifications.
