# Instagram Crew

Welcome to the **Instagram Crew** project, powered by **crewAI**! This template is designed to help you set up a multi-agent AI system with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable your agents to collaborate effectively on complex tasks, maximizing their collective intelligence and capabilities.

## Installation

To get started, ensure you have Python version **>=3.10 <=3.13** installed on your system. This project uses **Poetry** for dependency management, offering a seamless setup and execution experience.

1. **Install Poetry** (if you haven't already):
pip install poetry

Navigate to your project directory and install the dependencies:
poetry lock
poetry install

## Customizing
To customize your setup, follow these steps:
- Add your OPENAI_API_KEY into the .env file.
- Modify src/instagram/config/agents.yaml to define your agents.
- Modify src/instagram/config/tasks.yaml to define your tasks.
- Edit src/instagram/crew.py to add your own logic, tools, and specific arguments.
- Update src/instagram/main.py to include custom inputs for your agents and tasks.

## Running the Project

To kickstart your crew of AI agents and begin task execution, run the following command from the root folder of your project:

poetry run instagram
This command initializes the Instagram Crew, assembling the agents and assigning them tasks as defined in your configuration.

## Example

The unmodified example will create a report.md file in the root folder with the output of a research project on LLMs.

## Understanding Your Crew

The Instagram Crew consists of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks defined in config/tasks.yaml, leveraging their collective skills to achieve complex objectives. The config/agents.yaml file outlines the capabilities and configurations of each agent in your crew.

## Acknowledgments

Special thanks to Alejandro AO for the invaluable help with the notebook. Your tutorials have significantly improved this notebgook!
