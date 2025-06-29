# Crypto Research Crew

Welcome to the Crypto Research Crew project, powered by [crewAI](https://crewai.com). This template is designed to help you set up a multi-agent AI system focused on cryptocurrency and blockchain research with ease, leveraging the powerful and flexible framework provided by crewAI. Our goal is to enable your agents to collaborate effectively on crypto research tasks, maximizing their collective intelligence and capabilities in analyzing market trends, DeFi protocols, and blockchain innovations.

## Installation

Ensure you have Python >=3.10 <3.14 installed on your system. This project uses [UV](https://docs.astral.sh/uv/) for dependency management and package handling, offering a seamless setup and execution experience.

First, if you haven't already, install uv:

```bash
pip install uv
```

Next, navigate to your project directory and install the dependencies:

(Optional) Lock the dependencies and install them by using the CLI command:
```bash
crewai install
```
### Customizing

**Add your `GEMINI_API_KEY` and `SERPER_API_KEY` into the `.env` file**

- Modify `src/latest_ai_development/config/agents.yaml` to define your crypto research agents
- Modify `src/latest_ai_development/config/tasks.yaml` to define your crypto research tasks
- Modify `src/latest_ai_development/crew.py` to add your own logic, tools and specific args for crypto analysis
- Modify `src/latest_ai_development/main.py` to add custom inputs for your crypto research agents and tasks

## Running the Project

To kickstart your crew of AI agents and begin crypto research task execution, run this from the root folder of your project:

```bash
$ uv run latest_ai_development
```

This command initializes the Crypto Research Crew, assembling the agents and assigning them tasks as defined in your configuration.

This example will create a `report.md` file with the output of comprehensive research on cryptocurrency and blockchain trends in the root folder.

## Understanding Your Crew

The Crypto Research Crew is composed of multiple AI agents, each with unique roles, goals, and tools specialized for cryptocurrency and blockchain analysis. These agents collaborate on a series of tasks, defined in `config/tasks.yaml`, leveraging their collective skills to achieve complex crypto research objectives. The `config/agents.yaml` file outlines the capabilities and configurations of each agent in your crew:

- **Crypto Researcher**: Specialized in uncovering cutting-edge developments in cryptocurrency markets, DeFi protocols, and blockchain technology
- **Reporting Analyst**: Creates detailed reports based on crypto data analysis and research findings

## Support

For support, questions, or feedback regarding the Crypto Research Crew or crewAI.
- Visit our [documentation](https://docs.crewai.com)
- Reach out to us through our [GitHub repository](https://github.com/joaomdmoura/crewai)
- [Join our Discord](https://discord.com/invite/X4JWnZnxPb)
- [Chat with our docs](https://chatg.pt/DWjSBZn)

Let's create wonders together with the power and simplicity of crewAI in the cryptocurrency research space.
