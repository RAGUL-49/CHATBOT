# Billa – Mini AI Chatbot 🤖

Billa is a friendly AI assistant built using Google’s Gemini LLM. It helps with programming, software development, and tech questions, providing clear, step-by-step guidance.

## Features
- Friendly, supportive AI personality
- Explains programming concepts clearly
- Provides coding examples and best practices
- Context-aware responses and clarifying questions
- Step-by-step guidance for beginners and developers

## Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/mini-chatbot.git
Navigate to the project folder:

bash
Copy code
cd mini-chatbot
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
python
Copy code
from google.adk.agents.llm_agent import Agent

root_agent = Agent(
    model='gemini-2.5-flash',
    name='root_agent',
    description='''Your system prompt for Developer Ragul...''',
    instruction='''Your instructions for Billa...'''
)

response = root_agent.chat("Hi Billa, can you show me a Python example?")
print(response)

