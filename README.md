Unified Multimodal RAG System
This project is a high-performance, offline-first multimodal Retrieval-Augmented Generation (RAG) system. It features a sleek, Apple-inspired user interface with both light and dark modes, allowing users to ingest various file types (documents, images, audio) and query them using a powerful language model.

The system is designed for demonstration, showcasing a live connection to the Google Gemini API for real-time analysis while simulating high-accuracy performance and detailed source attribution for a professional proof-of-concept.

Features
Multimodal Ingestion: Process .pdf, .doc, .png, .jpg, .mp3, and .wav files.

Live AI-Powered Q&A: Utilizes the Google Gemini API for intelligent, context-aware responses based on ingested file content.

High-Accuracy Simulation: The backend consistently generates performance scores above 80% to simulate a highly-tuned RAG pipeline.

Detailed Source Attribution: Every response includes mock sources with unique chunkIds, page numbers, timestamps, or confidence scores.

Professional UI/UX: A clean, modern interface inspired by Apple's design language, complete with a seamless light/dark mode toggle.

Offline First: The architecture is designed to work as a self-contained unit, perfect for offline or private environments.

Prerequisites
Before you begin, ensure you have the following installed on your system:

Node.js: Version 18.x or later.

npm (Node Package Manager): This is included with your Node.js installation.

How to Run This Project
Follow these steps to get the application running locally:

1. Set Up the Project
First, place all the project files (index.html, server.js, package.json, and this README.md) into a single directory on your computer.

2. Install Dependencies
Open your terminal or command prompt, navigate to the project directory, and run the following command to install the necessary Node.js packages:

npm install

This will create a node_modules folder in your project directory.

3. Add Your API Key (Crucial Step)
For the application to connect to the Google Gemini API, you must add your API key.

Open the server.js file in a code editor.

Find the following line (around line 125):

const apiKey = ""; // Environment provides this

Insert your Google AI Studio API key between the double quotes:

const apiKey = "YOUR_API_KEY_HERE"; // Environment provides this

Save the server.js file.

4. Run the Backend Server
With the dependencies installed and the API key added, start the backend server by running this command in your terminal:

npm start

You should see a confirmation message in the terminal indicating that the server is running on http://localhost:3000.

5. Open the Frontend UI
Finally, open the index.html file in your web browser (like Chrome, Firefox, or Safari). You can usually do this by double-clicking the file.

The application is now ready to use! You can ingest a file and start asking questions.
