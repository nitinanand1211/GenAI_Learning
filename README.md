# GenAI_Learning


LangGraph Multi-Agent Workflow (Beyond LangChain)
This project demonstrates a multi-agent workflow using LangGraph, which offers capabilities beyond what is possible in traditional LangChain-based architectures.

Why LangGraph Over LangChain?

LangChain is sequential, meaning it follows a linear execution path.

LangGraph is conditional, enabling dynamic branching and decision-making in workflows.

LangGraph supports stateful, production-grade agentic architectures used by companies like LinkedIn, Uber, and Klarna.

 Stateful Agentic Approach
Every LangGraph agent must be created by defining a State.

The state is the medium through which the entire workflow communicates.

It helps pass information from one node to another in the graph.

A node in LangGraph is essentially a Python function that performs a task.

 Conditional Routing
Graphs can have conditional edges to allow dynamic flow:

How LangGraph Connects Nodes
All nodes are connected using edges.

These edges can be:

Static (always go to the same node)

Conditional (based on logic using the state)

🛠 Using LangChain Tools in LangGraph
You can integrate LangChain tools into LangGraph workflows. Learn more here:
🔗 LangChain Tools – Official Docs

