# Architecture

LGC Concept AI follows a separation-of-concerns model across both backend and frontend.

---

## Backend Architecture

Structured layers:

- Server bootstrap (entry layer)
- Express application configuration
- AI service abstraction
- Route-level mode handling
- MongoDB connection isolation

Each learning mode is processed independently via a unified `/ask` endpoint with mode-based routing logic.

This prevents mode blending and preserves clarity.

---

## Frontend Architecture

Frontend structure emphasizes:

- Clear entry positioning
- Mode-based navigation
- Reduced cognitive load
- Controlled switching between learning aspects

Pages are separated by learning intent:

- Learn
- Fast Learn
- Doubt
- Teach-Back

Navigation is standardized through a reusable switching component.

---

## Architectural Principles

1. Separation over clustering
2. Explicit state over implicit memory
3. Mode clarity over conversational blending
4. Version discipline over silent mutation

Architecture evolves intentionally across releases.
