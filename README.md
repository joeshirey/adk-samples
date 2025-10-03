# Agent Development Kit (ADK) Samples

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

<img src="https://github.com/google/adk-docs/blob/main/docs/assets/agent-development-kit.png" alt="Agent Development Kit Logo" width="150">

Welcome to the ADK Sample Agents repository! This collection provides ready-to-use agents built on top of the [Agent Development Kit](https://google.github.io/adk-docs/), designed to accelerate your development process. These agents cover a range of common use cases and complexities, from simple conversational bots to complex multi-agent workflows.

## ✨ Getting Started 
This repo contains ADK sample agents for both **Python** and **Java.** Navigate to the **[Python](python/)** and **[Java](java/)** subfolders to see language-specific setup instructions, and learn more about the available sample agents. 

> [!IMPORTANT]
> The agents in this repository are built using the **Agent Development Kit (ADK)**. Before you can run any of the samples, you must have the ADK installed. For instructions, please refer to the [**ADK Installation Guide**](https://google.github.io/adk-docs/get-started/installation).

To learn more, check out the [ADK Documentation](https://google.github.io/adk-docs/), and the GitHub repositories for [ADK Python](https://github.com/google/adk-python) and [ADK Java](https://github.com/google/adk-java). 

## 💡 ADK Features Demonstrated

This repository showcases a variety of agentic patterns and technical features of the ADK. Use the following guide to find examples of specific concepts:

### Agentic Patterns

| Pattern | Description | Samples |
| :--- | :--- | :--- |
| **Multi-Agent Systems** | Examples of how to build complex systems with multiple agents that collaborate to solve a problem. | [Academic Research](python/agents/academic-research), [Auto Insurance Agent](python/agents/auto-insurance-agent), [Blog Writer](python/agents/blog-writer), [Brand Search Optimization](python/agents/brand-search-optimization), [Financial Advisor](python/agents/financial-advisor), [Travel Concierge](python/agents/travel-concierge) |
| **Agents as Tools** | Demonstrates how to use one agent as a tool for another agent, enabling modular and reusable agent design. | [Academic Research](python/agents/academic-research), [Software Bug Assistant (Java)](java/agents/software-bug-assistant) |
| **Human-in-the-Loop** | Workflows that explicitly include steps for user feedback and refinement. | [Blog Writer](python/agents/blog-writer) |

### Technical Features

| Feature | Description | Samples |
| :--- | :--- | :--- |
| **`ApiHubToolset`** | Create tools from OpenAPI specifications stored in Apigee API Hub. | [Auto Insurance Agent](python/agents/auto-insurance-agent) |
| **`McpToolset`** | Dynamically load tools from a Model Context Protocol (MCP) server. | [Software Bug Assistant (Java)](java/agents/software-bug-assistant), [Time Series Forecasting (Java)](java/agents/time-series-forecasting) |
| **`FunctionTool`** | Create tools from simple Python functions. | [Blog Writer](python/agents/blog-writer) |
| **Built-in Tools** | Use out-of-the-box tools like `google_search`. | [Academic Research](python/agents/academic-research), [Software Bug Assistant (Java)](java/agents/software-bug-assistant) |
| **Web Browsing** | Create agents that can interact with websites using `selenium`. | [Brand Search Optimization](python/agents/brand-search-optimization) |
| **Multimodality** | Process and generate multiple types of data, such as text and images. | [Brand Search Optimization](python/agents/brand-search-optimization) |
| **BigQuery Integration** | Connect to BigQuery to query and analyze data. | [Brand Search Optimization](python/agents/brand-search-optimization), [Time Series Forecasting (Java)](java/agents/time-series-forecasting) |
| **State Management** | Manage conversational history and state across multiple turns. | All samples |
| **Authentication** | Handle API key authentication for tools, including retrieving secrets from Secret Manager. | [Auto Insurance Agent](python/agents/auto-insurance-agent) |

## 🌳 Repository Structure
```bash
├── java
│   ├── agents
│   │   ├── software-bug-assistant
│   │   └── time-series-forecasting
│   └── README.md
├── python
│   ├── agents
│   │   ├── academic-research
│   │   ├── blog-writer
│   │   ├── brand-search-optimization
│   │   ├── camel
│   │   ├── customer-service
│   │   ├── data-engineering
│   │   ├── data-science
│   │   ├── financial-advisor
│   │   ├── fomc-research
│   │   ├── gemini-fullstack
│   │   ├── google-trends-agent
│   │   ├── image-scoring
│   │   ├── llm-auditor
│   │   ├── machine-learning-engineering
│   │   ├── marketing-agency
│   │   ├── medical-pre-authorization
│   │   ├── personalized-shopping
│   │   ├── RAG
│   │   ├── realtime-conversational-agent
│   │   ├── safety-plugins
│   │   ├── README.md
│   │   ├── software-bug-assistant  
│   │   └── travel-concierge
│   └── README.md
└── README.md
```

## ℹ️ Getting help

If you have any questions or if you found any problems with this repository, please report through [GitHub issues](https://github.com/google/adk-samples/issues).

## 🤝 Contributing

We welcome contributions from the community! Whether it's bug reports, feature requests, documentation improvements, or code contributions, please see our [**Contributing Guidelines**](https://github.com/google/adk-samples/blob/main/CONTRIBUTING.md) to get started.

## 📄 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](https://github.com/google/adk-samples/blob/main/LICENSE) file for details.

## Disclaimers

This is not an officially supported Google product. This project is not eligible for the [Google Open Source Software Vulnerability Rewards Program](https://bughunters.google.com/open-source-security).

This project is intended for demonstration purposes only. It is not intended for use in a production environment.