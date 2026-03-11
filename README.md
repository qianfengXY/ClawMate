# ClawMate

**A personal super assistant built on top of OpenClaw’s skill ecosystem and orchestrated as domain-specific agents.**

ClawMate is a local-first personal super assistant system designed for developers, indie makers, and creators.

It treats **Skills** as reusable capability units, and **Agents** as long-running executors with memory, knowledge, and workflow logic. By combining OpenClaw’s fast-growing skill ecosystem with ClawMate’s domain-oriented agent design, the project aims to turn fragmented AI capabilities into a practical personal execution system.

ClawMate can be accessed through:
- **Open / ChatGPT** for conversations, project-style planning, and scheduled task entry points
- **OpenClaw** for persistent interactions across chat apps and local gateway-based environments

Instead of being “just another chatbot”, ClawMate is designed to become a **personal execution hub** that can research, build, review, deploy, and publish.

---

## Why ClawMate

Most AI tools are great at answering questions, but weak at sustaining work across time, context, and execution steps.

ClawMate is built around a different idea:

- **Skills provide breadth**
- **Agents provide depth**
- **Workflows provide continuity**
- **Memory provides personalization**

The goal is not only to call tools, but to build a system where each domain agent can:
- remember what matters
- keep its own knowledge base
- follow a repeatable workflow
- reuse high-quality community skills
- evolve over time without changing the user-facing interface

---

## Core Design Philosophy

ClawMate distinguishes clearly between **Skills** and **Agents**.

### Skills
Skills are reusable capability units.

A skill may wrap:
- a tool
- an API integration
- a content transformation step
- a search routine
- a publishing action
- a deployment helper
- a utility workflow

Skills are lightweight, replaceable, and composable.

### Agents
Agents are domain-specific executors.

An agent is responsible for:
- goal-oriented execution
- memory
- knowledge management
- workflow orchestration
- skill selection
- result formatting
- long-running behavior

In ClawMate, agents are not just collections of skills.  
They are role-based systems that combine skills with context, memory, and operating logic.

### The Principle
**Use community skills for capability coverage.  
Use ClawMate agents for stable execution, memory, and workflow control.**

---

## Positioning

ClawMate is **not** a plugin for Open.  
ClawMate is **not** just a skin over OpenClaw.

ClawMate is a **unified agent layer** that can be reached from multiple interfaces, while maintaining one coherent capability model underneath.

That means:
- Open / ChatGPT can be used for planning, discussion, and scheduled task entry points
- OpenClaw can be used for persistent messaging across chat apps
- ClawMate remains the stable orchestration and domain logic layer behind both

---

## Architecture Overview

```text
Interfaces
├── Open / ChatGPT
│   ├── conversation entry
│   ├── project-style context
│   └── scheduled task entry
└── OpenClaw
    ├── local dashboard / chat
    ├── gateway-based messaging
    └── chat-app integrations

ClawMate
├── Core
│   ├── task model
│   ├── context manager
│   ├── memory manager
│   ├── knowledge manager
│   └── result formatter
├── Flow
│   ├── workflow engine
│   ├── agent router
│   ├── skill selector
│   └── execution policies
├── Agents
│   ├── Insight Agent
│   ├── Build Agent
│   ├── Compliance Agent
│   ├── Secure Agent
│   ├── Deploy Agent
│   ├── Publish Agent
│   └── Studio Agent
└── Skills
    ├── Community Skills
    ├── Curated Skills
    └── Private Skills
