
# ADR-0001: Choose FastAPI for Backend

## Status
Accepted

## Context
We need a simple, modern Python web framework with OpenAPI support and type hints.

## Decision
Use **FastAPI** because it provides automatic OpenAPI docs, async support, and great DX.

## Consequences
- Faster prototyping and interactive docs at `/docs`.
- Python typing improves maintainability.
