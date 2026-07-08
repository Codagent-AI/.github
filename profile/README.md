# Codagent

The harness layer for dependable AI coding agents.

Codagent builds tools for teams that want AI agents to do real engineering work without turning delivery into a trust fall. The model matters, sure. But the bigger unlock is the system around it: planning, workflow control, validation, review, memory, and handoff.

Our thesis is simple:

> The answer is not a better model alone. It is a better harness around the model.

## What we are building

- [Agent Runner](https://github.com/Codagent-AI/agent-runner) - run coding agents inside explicit, repeatable workflows instead of asking the agent to manage the whole process from inside its own chat window.
- [Agent Validator](https://github.com/Codagent-AI/agent-validator) - put agent-generated changes through real checks, reviews, and quality gates. Vibes are not a test suite. Annoying, but true.
- [Agent Skills](https://github.com/Codagent-AI/agent-skills) - reusable skills for software-development tasks, so agents can follow known workflows instead of rediscovering basic engineering discipline every session.
- [Agent Plugin](https://github.com/Codagent-AI/agent-plugin) - install and expose agent plugins through native CLIs, with skills-based fallback where needed.
- [and-scene](https://github.com/Codagent-AI/and-scene) - agent-assisted visual storytelling and animated technical presentations.

## Design principles

Codagent is built around a few recurring harness-engineering patterns:

- Keep orchestration outside the agent session.
- Treat specs, plans, and validation results as durable artifacts.
- Separate planning from execution.
- Close the loop with verify/fix feedback cycles.
- Use cross-agent review when the work deserves a second set of model-shaped eyes.
- Preserve enough context and session state for humans and agents to pick work back up cleanly.

## Why this exists

Coding agents are already useful. They are also inconsistent, overconfident, and weirdly committed to making up APIs with the confidence of a principal engineer on espresso.

Codagent is about making agentic engineering more dependable by giving agents a better operating environment: scoped work, explicit constraints, observable execution, validation, and human-readable artifacts.

The goal is not to replace engineering judgment. The goal is to make AI-native engineering workflows legible, reviewable, and shippable.

## Follow along

- Organization: [github.com/Codagent-AI](https://github.com/Codagent-AI)
- Newsletter and writing: [Agents, Harnessed](https://github.com/Codagent-AI/newsletter)
