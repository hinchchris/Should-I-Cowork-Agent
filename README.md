# Should I Cowork Agent

A decision framework and Microsoft 365 Copilot agent that helps determine when to use:

- Copilot Chat
- Cowork
- Agents
- Copilot Studio

## What It Does

The Should I Cowork Agent evaluates a business scenario, task, or prompt and recommends the most appropriate Microsoft AI solution.

Based on the scenario, the agent will:

- Determine whether the task is best suited for Copilot Chat or Cowork
- Explain the reasoning behind the recommendation
- Estimate whether the Cowork request would be Light, Medium, or Heavy credit consumption
- Provide guidance on when an Agent or Copilot Studio solution may be a better fit
- Generate an optimized prompt when a standard Copilot Chat interaction is recommended

## Quick Start

See:

- Build-Agent.md
- Sample-Scenarios.md
- Prompt.md

## Example

### Input

"I need to gather project requirements from multiple documents, create a draft project plan, identify open questions, and prepare a stakeholder summary."

### Output

**Recommendation:** Cowork

**Reasoning:** This is a multi-step task requiring analysis across several sources with multiple deliverables.

**Estimated Usage:** Medium

**Suggested Next Step:** Use Cowork to review the source material, generate the project plan, identify gaps, and create a stakeholder-ready summary.

## Disclaimer

This project represents a decision framework based on real-world Microsoft Copilot adoption scenarios and is intended to help users select the best tool for a specific task.
