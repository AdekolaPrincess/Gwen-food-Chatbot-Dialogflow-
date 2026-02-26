# Gwen food Chatbot

## Project Overview

This project is a Dialogflow-powered chatbot integrated with a backend server and a SQL database.

The chatbot understands user intents, extracts entities, and triggers backend logic through Dialogflow Fulfillment (webhooks). The backend connects to a SQL database to retrieve and manage data dynamically.

This project was built by following a tutorial from Codebasics (Dhaval Patel) and then modified  by me to strengthen my understanding of conversational AI and backend integration.

---

## What I Learned

### 🔹 Dialogflow
- Creating and training Intents  
- Defining and using Entities  
- Configuring Fulfillment (Webhooks)  
- Testing and integrating the chatbot  

### 🔹 Backend Integration
- Connecting Dialogflow to a backend server  
- Handling webhook requests and responses  
- Connecting the backend to a SQL database  
- Structuring dynamic responses from database queries  

### 🔹 Ngrok
- Using ngrok to expose my local backend server  
- Generating a secure HTTPS public URL  
- Connecting the HTTPS URL to Dialogflow as a webhook endpoint  

### 🔹 SQL & Database Concepts
- Writing and modifying SQL queries  
- Understanding database structure and relationships  
- Tweaking the database schema to improve functionality  

---

##  Tech Stack

- Dialogflow  
- Python 
- SQL Database  
- Ngrok  
 

---

##  How It Works

1. A user sends a message to the chatbot.  
2. Dialogflow matches the message to an Intent.  
3. If fulfillment is enabled, Dialogflow sends a request to the backend webhook.  
4. The backend processes the request.  
5. The backend queries the SQL database (if needed).  
6. A structured response is returned to Dialogflow.  
7. Dialogflow sends the final response back to the user.  

---

##  Key Modifications

- Modified the database structure to better fit the chatbot logic  
- Adjusted backend logic for improved response handling  
- Strengthened intent matching and entity extraction  
- Ensured smooth end-to-end integration between Dialogflow, backend, and database  

---

## Learning Resource

Inspired by:
Codebasics YouTube Channel – Dhaval Patel  

The implementation was modified and extended as part of my personal learning process.

---

## Outcome

The chatbot successfully:
- Recognizes user intents  
- Extracts relevant entities  
- Connects to a backend server  
- Fetches data from a SQL database  
- Returns dynamic, accurate responses  

The system was tested end-to-end and works smoothly.
