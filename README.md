#  CNC Troubleshooting Chatbot

A simple AI-powered chatbot built using **Gradio** and hosted on **Google Colab** to assist CNC (Computer Numerical Control) machine operators in identifying and resolving common issues efficiently.

##  Features

- **Interactive Chatbot Interface**: Ask questions related to CNC machine issues and get relevant troubleshooting advice.
- **AI-Driven Responses**: Powered by a custom prompt engineering technique or LLM to simulate real-time assistant behavior.
- **Web UI via Gradio**: Easy-to-use interface running in your browser through Google Colab.

## Project Structure
CNC_Troubleshooting_Chatbot
┣ cnc_chatbot.ipynb ## Main Colab notebook
┗  README.md ## Project documentation


##  How It Works

The chatbot responds to common CNC-related queries using a predefined set of instructions or AI logic. It helps technicians and operators:
- Identify potential errors
- Understand error codes
- Follow safety procedures
- Perform quick fixes or maintenance steps

##  Getting Started

1. **Open the Notebook**  
   Launch the project in [Google Colab](https://colab.research.google.com/drive/1UNrEPjCxybmyqwUqarnFLQSduPDiT6O8).

2. **Run All Cells**  
   Press `Runtime > Run all` to start the chatbot.

3. **Interact with the Chatbot**  
   Use the Gradio UI to ask questions and receive help related to CNC machines.

##  Requirements

This project is designed to run in Google Colab. Dependencies are automatically installed when the notebook is executed, including:

- `gradio`
- `openai` (if using LLM)
- `os`, `json` (for configuration if needed)

##  Example Prompts

- "My CNC machine is showing alarm 100."
- "How do I fix spindle overheating?"
- "Why is the tool not changing?"
- "Machine stopped unexpectedly. What should I do?"



