# ADR 0001: Initial Project Architecture

## Status

Accepted

## Decision

The project will use a modular architecture with separate
components for:

- Frontend
- Backend
- Agents
- Tools
- Evaluation
- Documentation
- Tests

## Reason

A modular architecture makes it easier to replace individual
components without changing the entire system.

## Consequences

### Positive

- Easier experimentation
- Easier testing
- Clear separation of responsibilities
- Easier model/provider replacement

### Negative

- More initial project structure
- Additional integration work