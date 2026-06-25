# RAG — Retrieval-Augmented Generation

## Simple Definition

RAG is a pattern where an AI system retrieves relevant information from an external knowledge source and uses that information to generate a better answer.

## Human Analogy

Instead of answering from memory, the AI first opens the right documents, reads the relevant parts, and then answers.

## Basic Flow

1. User asks a question.
2. System searches documents or data.
3. Relevant chunks are retrieved.
4. The model receives the retrieved context.
5. The model generates an answer grounded in that context.

## Common Components

- documents
- chunking
- embeddings
- vector database or search index
- retriever
- prompt template
- model
- citations or source display
- evaluation

## Why RAG Matters

RAG helps AI systems answer using private, updated, or domain-specific knowledge that may not exist in the model’s training data.

## Product Lens

RAG is often the first practical enterprise AI architecture because companies already have documents, SOPs, tickets, policies, contracts, drawings, manuals, and knowledge bases.

## Failure Modes

- retrieving irrelevant chunks
- missing the right document
- poor chunking
- outdated source material
- hallucinating beyond the retrieved context
- no citation or source transparency

## Violet Connection

Violet AIOS can eventually become a personal RAG system. AEC use cases may include design standards, project documents, BIM manuals, construction checklists, safety protocols, and client requirements.

## Public References

- OpenAI Retrieval documentation
- IBM overview of Retrieval-Augmented Generation
- Azure AI Search RAG documentation

---

## How to Use This Note

- Keep this file as the polished concept note.
- Put messy course notes in `30_LEARNING/`.
- When a concept becomes useful for a project, link it from `20_PROJECTS/` or a separate implementation repo.

## Update Log

- Created: 2026-06-25
