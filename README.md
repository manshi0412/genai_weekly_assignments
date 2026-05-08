This repository contains the hands-on project that is required during the training of GEN AI.
It includes a basic chatbot and RAG system built using Python.
The goal of this project is to understand how LLM works and how external data can be used to improve responses.

FEATURES:
CHATBOT
simple LLM based chatbot
Takes user input and generates responses
Uses secure API Keys input via getpass()

RAG based QA Bot
upload abd read document(PDF)
split text into smaller chunks
convert text into embeddings
Retrieve relevant information

NEWS QA BOT
Fetches latest news from BBC using RSS Feed
extracts title and summary of articles
Stores them as text data
Uses LLM + RAG to answer questions based on news

AI TEST CASE GENERATOR
Accepts plain‑English business requirements
Uses ReAct (Reason + Act) prompting to analyze scenarios
Generates structured test cases (positive, negative, edge cases)
Applies jailbreak defense to block malicious prompts
Performs PII redaction on inputs and outputs to protect sensitive data

TECH STACK
Python(3.12.15)
Langchain
llama
openAI LLM
Google colab
