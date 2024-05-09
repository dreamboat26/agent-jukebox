# LangChain Custom Tools & Agents

This script demonstrates the usage of LangChain custom tools and agents for natural language processing tasks.

## Overview

LangChain provides a framework for building and deploying custom tools and agents tailored to specific language-related tasks. These tools and agents can perform a variety of functions, such as web searches, answering questions, and providing information on specific topics.

## Tools

### DuckDuckGoSearchTool

- **Description**: Performs web searches using the DuckDuckGo search engine.
- **Functionality**: Useful for answering questions about current events. It is recommended to ask targeted questions.
- **Usage Example**: `search("Your search query")`

### RandomTool

- **Description**: Generates a random number.
- **Functionality**: Provides a random number upon request.
- **Usage Example**: `random_tool()`

### MeaningOfLifeTool

- **Description**: Provides information about the meaning of life.
- **Functionality**: Returns the meaning of life upon request. Input should be "MOL".
- **Usage Example**: `meaning_of_life("MOL")`

## Agents

### Conversational Agent

- **Description**: A conversational agent that utilizes the defined tools to respond to user queries.
- **Memory**: Utilizes a ConversationBufferWindowMemory to store past chat history.
- **Initialization**: The agent is initialized with specified tools, language model, and memory settings.
- **Usage Example**:
    ```python
    conversational_agent("What time is it in London?")
    conversational_agent("Can you give me a random number?")
    conversational_agent("What is the meaning of life?")
    ```

## Getting Started

To use LangChain custom tools and agents:

1. **Import Tools**: Import the desired tools from `langchain.tools`.
2. **Initialize Agents**: Initialize agents with the required tools, language models, and memory settings.
3. **Execute Queries**: Use the agents to process user queries and obtain responses.

## Acknowledgments

This script utilizes LangChain tools and agents to demonstrate the capabilities of the framework for natural language processing tasks.

For more information, refer to the LangChain documentation and resources.

Let's enhance language processing with LangChain custom tools and agents!


