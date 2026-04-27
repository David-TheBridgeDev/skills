# skills

A repository of skills I use to work with AI agents. These skills are designed to enhance productivity, code architecture, and the development process through structured workflows.

## Installation

To install any of these skills, use the following format:

```bash
npx skills@latest add David-TheBridgeDev/skills/[Skill-Name]
```

Replace `[Skill-Name]` with the name of the folder of the skill you wish to install.

## List of Skills

| Skill | Description | When to Use |
| :--- | :--- | :--- |
| 🪨 **caveman** | Ultra-compressed communication mode. Reduces token usage by removing filler and pleasantries. | When you want to save tokens or prefer extremely brief and technical responses. |
| 🎨 **design-an-interface** | Generates multiple radically different interface designs for a module. | To design APIs, explore interface options, or compare the shape of different modules. |
| 🏗️ **domain-model** | Intensive grilling session to challenge a plan against the existing domain model and documented decisions. | To stress-test a plan against project language and documented decisions (ADRs). |
| 🥩 **grill-me** | Relentless interview about a plan or design until reaching a shared understanding. | When you want the agent to question every detail of your design or implementation plan. |
| 🏛️ **improve-codebase-architecture**| Finds deepening opportunities in a codebase, turning "shallow" modules into "deep" ones. | To improve testability, consolidate coupled modules, and make the codebase more AI-navigable. |
| 🐞 **qa** | Interactive QA session to report bugs and issues conversationally. | To perform testing, report bugs, and file structured GitHub issues. |
| 📝 **request-refactor-plan** | Creates a detailed refactoring plan with tiny commits and generates a GitHub RFC. | To plan complex refactors in a safe and incremental way. |
| 🚦 **tdd** | Test-driven development with a red-green-refactor loop. | To build features or fix bugs ensuring tests verify behavior, not implementation. |
| 🎫 **to-issues** | Breaks a plan, spec, or PRD into independently grabbable GitHub issues using vertical slices. | To convert a high-level strategy into concrete implementation tasks. |
| 📄 **to-prd** | Synthesizes the current conversation context into a Product Requirements Document (PRD). | To formalize a technical idea or discussion into an official product document on GitHub. |
| 🚑 **triage-issue** | Investigates the root cause of a bug and proposes a TDD-based fix plan. | When a problem is reported and you need a deep technical diagnosis and action plan. |
| 📖 **ubiquitous-language** | Extracts and formalizes a DDD-style ubiquitous language glossary from the conversation. | To unify language between developers and domain experts in the project. |
| ✍️ **write-a-skill** | Guide for creating new agent skills with proper structure and bundled resources. | When you need to create a new capability or automated workflow for the agent. |
| 🔍 **zoom-out** | Requests a high-level perspective or a map of relevant modules and dependencies. | When the agent (or you) are unfamiliar with a section of code and need the "big picture". |

## Skill Structure

Each skill resides in its own directory and contains at least a `SKILL.md` file defining its name, description, and behavioral rules. Some skills include additional reference files (`REFERENCE.md`, `LANGUAGE.md`, etc.) to delve into specific concepts.
