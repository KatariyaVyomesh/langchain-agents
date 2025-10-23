# 📌 LangChain Agents (2025)

LangChain Agents are intelligent components that combine **Large Language Models (LLMs)** with **tools or APIs** to autonomously solve complex tasks. Unlike standard LLMs that only generate text, agents **reason, plan, and take actions** based on the user query.

---

## **1️⃣ Agent Prompts from LangChain Hub**

LangChain Hub provides prebuilt **agent prompts** to help developers quickly set up agents for various use cases.  

| Prompt Name | Description | Use Case |
|-------------|-------------|---------|
| Zero Shot Agent | Agent decides which tool to use without examples | Simple, dynamic task execution |
| ReAct Agent | Uses reasoning + acting in steps | Complex multi-step reasoning |
| Conversational Agent | Maintains context in a conversation | Chatbots with memory |
| Plan-and-Act Agent | Plans multiple steps before execution | Multi-tool workflows |
| Tool-Using Agent | Uses multiple external tools to answer queries | Retrieval, API calls, or calculations |

> You can find all prompts on the [LangChain Hub](https://www.langchain.com/hub).

---

## **2️⃣ Types of LangChain Agents**

| Agent Type | Description | Use Case |
|------------|-------------|---------|
| Zero Shot Agent | Chooses actions without examples | Quick tool integration |
| ReAct Agent | Combines reasoning and actions step-by-step | Multi-step problem solving |
| Conversational Agent | Maintains dialogue context | Chatbots or virtual assistants |
| Plan-and-Act Agent | Plans all steps first, then executes | Complex workflows with multiple tools |
| Agent with Memory | Remembers past interactions | Personalized assistants |
| LLM-Aided Agent | Uses LLM for reasoning with structured outputs | Data analysis, document QA |
| Custom Agent | Fully customized logic and toolset | Any domain-specific automation |

---

## **3️⃣ How Agents Work**

1. **Observe** → Analyze the query or environment.  
2. **Decide** → Pick the tool or action.  
3. **Act** → Execute the chosen tool.  
4. **Repeat** → Continue until the goal is achieved.  

**Example Conceptual Flow:**
User: "Find the latest stock price of Tesla and its market news."
Agent:

Call stock price API → get Tesla price

Call news API → get recent news

Combine results → Respond to user



---

## **4️⃣ Key Benefits**

- Multi-step reasoning  
- Dynamic tool usage  
- Conversational memory  
- Customizable workflows  
- Suitable for RAG (Retrieval-Augmented Generation) pipelines  

---

## **5️⃣ References**

- [LangChain Documentation](https://www.langchain.com/docs/)  
- [LangChain Hub](https://www.langchain.com/hub)  

