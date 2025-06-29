# Using CrewAI to Brainstorm Research Ideas with Autonomous Agents

This project demonstrates how to use CrewAI to automatically generate, evaluate, and refine research ideas using a team of large language model (LLM)-based agents.

## Objective

The goal is to simulate a structured research ideation workflow using autonomous agents that can:

1. Propose a wide range of research ideas
2. Enrich them with literature insights
3. Critically evaluate their quality
4. Output a full research proposal prompt or outline

This workflow is useful for exploring **Generative AI applications in healthcare or other domains**.

## Key Components

The project uses four CrewAI agents:

| Agent Role        | Description                                                    |
|-------------------|----------------------------------------------------------------|
| `ResearchPlanner` | Generates diverse research ideas on a given topic              |
| `ResearchAnalyst` | Adds supporting academic literature and examples               |
| `ResearchCritic`  | Evaluates each idea's feasibility, novelty, and potential impact |
| `Researcher`      | Writes a detailed proposal or summary based on the best idea   |

Agents communicate through defined `Tasks`, forming an iterative and adaptive workflow.
