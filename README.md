# 🦁 Zoo Guide AI Agent

An intelligent AI-powered Zoo Tour Guide that helps users explore animals in a zoo by combining internal zoo data with external knowledge (Wikipedia).

Built using Google ADK (Agent Development Kit) and LangChain tools, this project demonstrates how multi-agent systems can collaborate to deliver rich, conversational responses.

---

## 🚀 Live Demo  
🔗 View Agent:  

---

## 🚀 Features
- 🤖 Multi-agent AI architecture
- 🔍 Combines zoo-specific data + Wikipedia knowledge
- 🧠 Intelligent prompt analysis
- 🗣️ Friendly, conversational responses
- 🔄 Sequential agent workflow
- 🧩 Modular and extensible design

---

## 🏗️ Project Architecture

This project uses a multi-agent pipeline:

1. 🧠 Greeter Agent
- Entry point of the system
- Welcomes the user
- Stores user query in state
  
2. 🔍 Researcher Agent
- Analyzes user prompt
- Decides which tools to use
- Fetches:
-- Zoo-specific data (internal)
--General knowledge via Wikipedia

3. ✨ Response Formatter Agent
- Converts raw research into:
-- Friendly
-- Structured
-- Engaging responses

4. 🔄 Sequential Workflow

All agents are connected using a SequentialAgent pipeline:

Greeter → Researcher → Formatter → Final Response

---

## 🛠️ Tech Stack

- Google ADK – Agent orchestration
- LangChain – Tool integration
- Wikipedia API – External knowledge
- Python – Core implementation

---

## 📂 Project Structure

    ZOO-GUIDE-AGENT/
    │── agent.py            # Main agent logic
    │── requirements.txt    # Dependencies
    │── .env                # Environment variables
    │── __init__.py

---

## 🧠 How It Works
1. User enters a query
2. Greeter stores the prompt
3. Researcher:
- Decides which tools to use
- Fetches relevant data
4. Formatter:
- Converts data into human-friendly response

---

### ⭐ Don’t forget to give this project a star if you like it!
