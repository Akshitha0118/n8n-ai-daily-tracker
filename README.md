# 🚀 n8n-ai-daily-tracker

Turn your daily routine into a conversation.
An AI-powered daily routine tracker built using n8n, Google Gemini, and Google Sheets.

## 📌 Overview

This project is a workflow automation system that acts as a conversational productivity assistant.
Instead of manually logging tasks, you can simply chat with an AI, and it will:

Understand your intent

Store your daily activities

Retrieve and summarize your tasks

All powered by LLM + automation ⚡

## ✨ Features

✅ Chat-based task logging

✅ AI-powered intent understanding

✅ Context-aware conversations using memory

✅ Google Sheets as a lightweight database

✅ Fully automated workflow using n8n

✅ Real-time task tracking & retrieval


## 🧩 Workflow Architecture

This project uses a modular n8n workflow:

### 🔹 Components

Trigger Node

Starts workflow when a chat message is received

AI Agent

Processes user input

Decides actions based on intent

Chat Model

Google Gemini for natural language understanding

Memory

Maintains conversation context

Google Sheets Tool

Stores and retrieves daily logs

## ⚙️ Flow

User sends a message (e.g., "Add gym at 6 PM")

AI Agent interprets the request

Memory maintains context

Data is stored/retrieved from Google Sheets

AI responds with confirmation or results

## 🛠️ Tech Stack

n8n – Workflow automation

Google Gemini – LLM for chat processing

Google Sheets – Data storage

AI Agent + Memory – Context-aware logic

## 🚀 Setup Instructions
## 1️⃣ Prerequisites

n8n account (cloud or self-hosted)

Google account

Gemini API key

## 2️⃣ Setup Steps
### 🔹 Step 1: Import Workflow

Open n8n

Import your workflow JSON

### 🔹 Step 2: Configure Gemini

Add API key in credentials

Connect it to the Chat Model node

### 🔹 Step 3: Setup Google Sheets

Create a sheet with columns like:

Task | Time | Date | Status

Connect Google Sheets node with credentials

### 🔹 Step 4: Connect Nodes

Trigger → AI Agent

AI Agent → Gemini Model

AI Agent → Memory

AI Agent → Google Sheets

### 🔹 Step 5: Activate Workflow

Click Activate

## Start chatting 🎉

💡 Example Use Cases

💬 “Add meeting at 10 AM”
📊 “What did I do today?”
📅 “Show my tasks for this week”
📈 “Give me productivity summary”

## 📸 Screenshots

Add your workflow screenshot here



