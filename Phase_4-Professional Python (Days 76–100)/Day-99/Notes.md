# Day 99 Notes — CLI Layer

## Purpose of CLI Layer

The CLI:
- Parses arguments
- Instantiates dependencies
- Calls service methods
- Prints results

It does NOT:
- Contain business logic
- Handle persistence directly
- Make validation decisions

---

## Storage Path Strategy

- Default: tasks.json
- Optional: --storage custom_path.json

CLI decides path.
Repository receives it.

---

## Error Handling

CLI should:
- Catch ValueError
- Print friendly message
- Exit gracefully

Service should:
- Raise meaningful errors

Separation is critical.


