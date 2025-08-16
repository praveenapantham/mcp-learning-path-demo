# 🚀 MCP Mega Workshop – AI Automation Projects

This repository contains **5 AI automation projects** I built using **Cursor + Model Context Protocol (MCP) + APIs**.  
Each project focuses on solving a real-world task using automation, AI integration, and MCP-powered workflows.

---

## 📂 Projects Overview

### 1. LinkedIn Post Generator
An automation tool that creates **professional LinkedIn posts** in seconds.  
It integrates AI to generate engaging content and adds **auto-generated images** for better presentation.  
This project helps in maintaining a consistent online presence without manual effort.

#### Cursor IDE Automation
<img width="437" height="909" alt="image" src="https://github.com/user-attachments/assets/db471a5f-f84f-4377-9af0-862dcd5f24c9" />

#### Linked Post Created
Check here "https://www.linkedin.com/posts/praveena-pantham_nxtwave-mcp-aiworkflows-activity-7357718692836626432-d9Wk?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD1vokYBigT19_Y-Eyeyvds9HIHBUWkNId4"
<img width="713" height="844" alt="image" src="https://github.com/user-attachments/assets/bf5aaab3-6918-46e8-8cf2-5780ba5d0152" />


### 2. Gmail Automation
A smart email automation system that connects with Gmail via APIs.  
It can **fetch the latest emails** and generate AI-powered draft replies.  
This reduces the time spent on routine communication and improves productivity.

### 3. Railway Status Tracker
A real-time railway tracking project powered by MCP servers and public APIs.  
It provides **up-to-date train schedules, delays, and running status**.  
Built with automation in mind, it showcases how MCP can be used in real-time data applications.

### 4. ElevenLabs Voice Automation
An AI voice generation tool using the **ElevenLabs API**.  
It converts plain text into **natural-sounding human-like speech**.  
This project demonstrates how MCP + APIs can enable personalized content creation and accessibility features.

### 5. Learning Path Generator
A Streamlit-based app that generates **personalized learning paths** using MCP.  
It integrates with **YouTube, Google Drive, and Notion** to create a complete learning experience.  
The app suggests content, organizes notes, and helps track progress in real time.

---

# 🎯 Learning Path Generator with Model Context Protocol (MCP)

This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.
## Live Demo
<img width="1919" height="1019" alt="image" src="https://github.com/user-attachments/assets/963f9e63-00bf-4bd8-a438-914592c6d514" />


## Features

- 🎯 Generate personalized learning paths based on your goals
- 🎥 Integration with YouTube for video content
- 📁 Google Drive integration for document storage
- 📝 Notion integration for note-taking and organization
- 🚀 Real-time progress tracking
- 🎨 User-friendly Streamlit interface

## Prerequisites

- Python 3.10+
- Google ai Studio API Key
- Pipedream URLs for integrations (YouTube and either Drive or Notion)

## Installation

1. Clone the repository:

2. Create and activate a virtual environment:

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Configuration

Before running the application, you'll need to set up:

1. Google API Key
2. Pipedream URLs for:
   - YouTube (required)
   - Google Drive or Notion (based on your preference)

## Running the Application

To start the application, run:
```bash
streamlit run app.py
```

The application will be available at `http://localhost:8501` by default.

## Usage

1. Enter your Google AI studio API key and Pipedream URLs in the sidebar
2. Select your preferred secondary tool (Drive or Notion)
3. Enter your learning goal (e.g., "I want to learn python basics in 3 days")
4. Click "Generate Learning Path" to create your personalized learning plan

## Project Structure

- `app.py` - Main Streamlit application
- `utils.py` - Utility functions and helper methods
- `prompt.py` - Prompt template
- `requirements.txt` - Project dependencies

## 🛠️ Tech Stack
- Python 3.10+, Streamlit  
- Model Context Protocol (MCP)  
- Cursor IDE  
- Google AI Studio, Pipedream APIs  
- ElevenLabs API, Gmail API, Railway API  
