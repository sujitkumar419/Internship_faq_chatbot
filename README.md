# 🤖 Internship FAQ Chatbot | StaxTech AI Project

This repository contains **Project 1** of my Artificial Intelligence internship at **StaxTech**.  
It’s a simple yet powerful chatbot built using **Rasa**, designed to answer frequently asked questions about internships—like a digital senior guiding juniors.

## 🔧 Features
- Answers FAQs like:
  - Internship start date
  - Certificate availability
  - Internship mode (remote/offline)
- Built using Rasa framework
- Easy to train, customize, and expand

## 📁 Files
- `nlu.yml`: Contains training examples
- `domain.yml`: Defines intents and responses
- `stories.yml`: Conversation flow
- `config.yml`: Pipeline configuration

## 🚀 Run the Bot
```bash
rasa train
rasa shell
