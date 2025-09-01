#kiri - Your new ai study assistant 

Kiri is a desktop application built with Python and PyQt5 that helps you transform PDF documents into structured notes and generate various study materials using the power of local Large Language Models (LLMs) via Ollama.

It allows you to process PDFs, summarize their content, ask questions about the material, and create Q&A sets, practice questions, and brief overviews, all stored locally for easy access and export.

Features
PDF Processing: Load and extract text from PDF files.
AI-Powered Summarization: Generate detailed, bullet-point summaries of PDF content using local LLMs (configured for gemma3:4b-it-qat).
Local AI Integration: Utilizes the Ollama API to run models locally, ensuring privacy and offline capability.
Content Generation: Create different types of study materials from your saved notes
no need for wifi: works offline 
Privacy: It does not interfere with any tasks on your device
Summaries
Brief Overviews
Q&A Sets
Practice Questions
Professor Mode (Interactive Q&A): Ask specific questions about any saved note and receive AI-generated answers based on that note's content.
Note Management: Save generated summaries and content as notes in a local JSON file (pdf_notes.json). View, select, and delete saved notes.
Export to Word: Export generated summaries, notes, and other content to editable Microsoft Word (.docx) documents.
Dark Theme UI: Features a sleek black and blue themed graphical user interface built with PyQt5 for comfortable use
