# mermaid
Mermaid diagrams repo

# 🧭 Mermaid Playground

This repo is my personal sandbox for learning and collecting **Mermaid diagrams**.  
It’s a mix of cheatsheets, examples, and reusable snippets.

---

## Quick Example (Statistical Data Types and Levels of Measurement)

```mermaid
flowchart TD
    A[DATA TYPES] --> B[CATEGORICAL]
    A --> C[NUMERICAL]

    B --> B1[NOMINAL - Gender, Colour]
    B --> B2[ORDINAL - Satisfaction Rating]

    C --> C1[INTERVAL]
    C --> C2[RATIO]

    C1 --> C1a[DISCRETE - Calendar Years]
    C2 --> C2b[CONTINUOUS - Height, Weight, Age]
