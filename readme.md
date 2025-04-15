Setup
python3 -m venv agent_env 
source agent_env/bin/activate

# AI Agent Example Project
  This repository contains a simple AI agent workflow stringing together various elements that utilize the OpenAI API. This application classifies, summararizes, and extracts key values from a provided text string. The original project can be found here: https://medium.com/data-science-collective/the-complete-guide-to-building-your-first-ai-agent-its-easier-than-you-think-c87f376c84b2

# Setup

Create and activate a virtual environment:

```bash
python3 -m venv agent_env
source agent_env/bin/activate
```

Install necessary packages:

```bash
pip install langgraph langchain langchain-openai python-dotenv
```
Set up your OpenAI API:

```bash
echo "OPENAI_API_KEY=your-api-key-here" > .env
```

# Run the Application

Modify the sample_text variable in the agent.py file to fit your needs. Run the following to execute the workflow:

```bash
python agent.py
```
