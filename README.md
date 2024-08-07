# Cubet Assignment 

## Problem Statement

We expect you to create an assignment related to GenAI.

Steps of Assignment

1. Create a RAG based chatbot using any open source models(LLaMa2, LLaMa3, Mistral
etc.)

2. Query from multiple documents
   
3. Improve the performance of Retrieval(control what goes to the LLM model)
    
4. You should use the documents that are shared with you with this email.
 
Note: The query should be asked from multiple sources in a single query.

## Solution 
Approach 1 - Simple RAG system
Approach 2 - Agentic RAG system

The limitations of the first approach is overcome on the second one.

## How to run the project?
I have created a main.py file which uses Agentic RAG and the jupyter notbeook includes the detailed code of simple RAG Approach and Agentic RAG approach. Can make use of streamlit to provide the user interface.

How to run the main.py file

  1.Clone the project using the https url.

  2.Create a virtual envirionment using virtualenv
    
  3.Install the requirements.txt using pip install -r requirements.txt

  4.Create a directory called 'cubet_pdfs' and put all the files in there (Make sure to provide pdfs only as I have tried with pdf loader for now).
   
  5.If you are using openai then you need to provide the openai key by creating a .env file
   
  6.If you are using opensource llms then you need to install ollama -  THe installation link is given below
   
    https://ollama.com/
