# NewsletterGen Crew

Welcome to the NewsletterGen Crew project, a multi-agent AI system built using crewAI. This project allows multiple AI agents to collaborate on tasks, leveraging their collective intelligence.

## Table of Contents

- [Installation](#installation)
- [Customization](#customization)
- [Running the Project](#running-the-project)
- [Understanding Your Crew](#understanding-your-crew)

## Installation

Ensure you have Python 3.10 to 3.13 installed on your system. Use Poetry for dependency management. After installing Poetry, navigate to your project directory and run the following commands:

poetry lock
poetry install

## Customization

To customize your project, follow these steps:
- Add your OPENAI_API_KEY to the .env file.
- Modify the src/newsletter_gen/config/agents.yaml file to define your agents.
- Modify the src/newsletter_gen/config/tasks.yaml file to define your tasks.
- Modify the src/newsletter_gen/crew.py file to add your own logic, tools, and specific arguments.
- Modify the src/newsletter_gen/main.py file to add custom inputs for your agents and tasks.

## Running the Project

To start your crew of AI agents and execute tasks, run the following command from the root folder of your project:
poetry run newsletter_gen : This command initializes the NewsletterGen Crew, assembles the agents, and assigns them tasks as defined in your configuration.

## Understanding Your Crew

Your NewsletterGen Crew is composed of multiple AI agents, each with unique roles, goals, and tools. These agents collaborate on a series of tasks, defined in config/tasks.yaml, leveraging their collective skills to achieve complex objectives. The config/agents.yaml file outlines the capabilities and configurations of each agent in your crew.

This project, unmodified, will run the create a report.md file with the output of a research on LLMs (Large Language Models) in the root folder.

## Acknowledgement
Alejandro AO for the tutorial 





    
    
