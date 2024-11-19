# Crick_Chat 🏏
### 🏏 AI-Powered Application for Quick Cricket Player Insights 🧠


## 🌟 Overview
This project is an AI-powered application that delivers quick and detailed insights into the careers and performances of cricket players. 
By leveraging the power of open-source Large Language Models (LLMs) like Mistral and Llama, users can easily access player statistics and news without exhaustive searching.
It's your go-to platform for cricket analytics! 🏟️



## ✨ Features
🔍 Player Insights: Detailed performance insights for any cricket player.
📊 Cross-format Coverage: Supports ODIs, Tests, T20 Internationals, and IPL.
📅 Year-based Filtering: Get stats for a specific time frame.
🖥️ User-friendly Interface: Built using Streamlit for a seamless experience.
🔐 Local Model Integration: Ensures privacy and efficiency with locally run LLMs.




## 🛠️ Technology Stack
📚 Libraries and Tools
LangChain: For workflow design and integration with Ollama models.
Ollama: Local LLM model runner for secure, fast processing.
Streamlit: For an interactive and visually appealing UI.




## 🧩 Key Dependencies
langchain-ollama
streamlit
langchain
python-box
uvicorn
ollama





## 🚀 Installation Guide
Clone the Repository: git clone https://github.com/your-repo-name.git
cd your-repo-name

Set Up a Virtual Environment: python -m venv .venv
 for mac ,use :- source .venv/bin/activate  
 On Windows, use `.venv\Scripts\activate`

Install Dependencies:pip install -r requirements.txt

Run Ollama Locally:
Ensure the Ollama service is running on http://localhost:11434/ with the required LLM models (e.g., Llama3.2).

Start the Application: streamlit run ChatBot.py





## 🎮 How to Use
Open the app in your browser. It typically runs at http://localhost:8501.
🎯 Enter the player name, select the cricket format, and specify the year range.
🏆 Click Generate to get detailed player insights.
💬 Interact with the Chat History to revisit previous queries and responses.





## 🛠️ Application Workflow
Input Gathering: User inputs (player name, format, year) are collected via the UI.
Prompt Formatting: Inputs are structured into a predefined template for LLM processing.
Response Generation: Insights are generated using the LLM and displayed in the app.
Chat History: Maintains a record of all user queries and responses.




## 📂 Code Structure
ChatBot.py: Main script for the application. Contains logic for UI, prompt formatting, and LLM integration.
Prompt Template: A structured template for generating actionable prompts for the LLM.





## 🎯 Features for the Future
🏏 Expand support to additional cricket leagues and tournaments.
📈 Add advanced filtering options for specific matches, teams, or venues.
🌍 Introduce multilingual support for global accessibility.


## 🖼️ Screenshots

