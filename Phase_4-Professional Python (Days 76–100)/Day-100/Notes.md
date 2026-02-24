# Day 100 Notes — Hardening & Logging

## Why Logging Matters

Print statements help users.
Logging helps developers.

Logging allows:
- Tracing behavior
- Diagnosing failures
- Observing system state

Logging should not:
- Replace error handling
- Expose sensitive data
- Create noise

---

## Logging Strategy

We will:
- Use Python's built-in logging module
- Log key service operations
- Log errors at appropriate levels
- Keep logs simple and structured

---

## What We Will NOT Do

- Add complex logging frameworks
- Overconfigure loggers
- Log excessively

Professional polish means restraint.

---

## Final Review Checklist

- Layers remain separated
- No circular dependencies
- Tests pass
- CLI thin
- Repository defensive
- Business rules enforced
- Logging helpful, not noisy

Professional software is predictable.