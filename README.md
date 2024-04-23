# Llama3+Crewai+Groq 

The implementation involves agents collaborating to streamline the email writing task. The overview of the task description is as follows:

## The goal

Reply to a customer email
1. get the email
2. categorize this as a "sales", "custom enquiry", "off topic", "customer complaint"
3. use the category to research info needed for the reply
4. take the info and check if there is enough to answer the email
5. write a reply
6. check the reply
7. save the email

### Agents
- categorizer
- researcher (web for now would be internal RAG)
- email writer


### Tasks
- categorize email
- research the answer
- write the email

### Model Used - Llama3-70b 

These screenshots capture Agents in Action, showcasing their thoughtful process. They depict how the research agent conducts investigations based on customer inquiries. The images below illustrate various inquiry cases and how agents collaborate to respond collectively, even handling contentious emails from customers.

![1](https://github.com/dreamboat26/agent-jukebox/assets/125608791/ad3eefe0-93c1-4037-80c3-4f9f1a03c835)

"It demonstrates how the agents respond to a positive email from the customer."

![2](https://github.com/dreamboat26/agent-jukebox/assets/125608791/bc2575c0-ccd4-4ce0-b863-367c319fe26a)

"It illustrates how the research agent searches for the query and returns it to the email writer agent to incorporate the details into the email and finalize the writing process effectively."

![3](https://github.com/dreamboat26/agent-jukebox/assets/125608791/9667d47f-7b5f-4af7-9146-c9d429250df9)

"It showcases how the agent addresses the customer's questions on a contentious topic."

![4](https://github.com/dreamboat26/agent-jukebox/assets/125608791/5debc146-3715-4c00-9a77-8c6e3b7ab3e1)

"It demonstrates the quantification of the query based on the email category, along with the research information provided."


