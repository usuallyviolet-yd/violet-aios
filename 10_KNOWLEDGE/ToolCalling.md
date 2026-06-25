# Tool Calling

## Simple Definition

Tool calling lets an AI model use external functions, APIs, or systems instead of only generating text.

## Human Analogy

Instead of only giving advice, the AI can use a calculator, search a database, create a calendar event, run code, or call an enterprise API.

## Basic Flow

1. Developer defines available tools.
2. Model decides whether a tool is needed.
3. Model produces structured arguments for the tool.
4. Application executes the tool.
5. Tool result returns to the model.
6. Model continues or gives final answer.

## Why Tool Calling Matters

Tool calling turns LLMs from text generators into workflow participants. It allows AI systems to access live data and take actions.

## Product Examples

- check order status
- query CRM
- search project documents
- create a support ticket
- update a database
- calculate quantities or cost
- generate and save a file

## Risks

- wrong tool selection
- malformed arguments
- unsafe action execution
- data leakage
- missing human approval
- over-trusting tool results

## Product Lens

Tool calling needs careful UX design. Users should understand what the AI is doing, what data it is using, and when approval is required.

## Violet Connection

Tool calling is foundational for agents, MCP, enterprise AI workflows, and future AEC/Spatial AI assistants.

## Public References

- OpenAI Function Calling documentation

---

## How to Use This Note

- Keep this file as the polished concept note.
- Put messy course notes in `30_LEARNING/`.
- When a concept becomes useful for a project, link it from `20_PROJECTS/` or a separate implementation repo.

## Update Log

- Created: 2026-06-25
