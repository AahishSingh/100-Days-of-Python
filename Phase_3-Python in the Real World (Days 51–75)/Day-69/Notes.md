# Day 69 Notes — Threads in Python

## What Threads Actually Do in Python

Threads allow:
- Multiple tasks to make progress
- While others are waiting (I/O)

They do NOT:
- Run Python bytecode in parallel (in default CPython)
- Speed up CPU-heavy computation

---

## When Threads Help

Threads are ideal for:
- Network requests
- File I/O
- Sleeping / waiting
- User input
- External APIs

In these cases, threads improve **responsiveness and throughput**.

---

## When Threads Hurt

Threads hurt when:
- Tasks are CPU-bound
- Shared state is mutated carelessly
- Synchronization is ignored

More threads ≠ more speed.

---

## The GIL Reminder

Because of the GIL:
- Only one thread executes Python bytecode at a time
- Threads interleave execution, they don’t parallelize computation

This is fine for I/O-bound workloads.

---

## Thread Lifecycle (Simple)

1. Create thread
2. Start thread
3. Thread runs independently
4. Join thread (wait for completion)

Always join unless you *explicitly* want background behavior.

---

## Mental Rules

> Use threads to **wait better**, not compute faster.  
> If code waits → threads help.  
> If code computes → threads don’t.

Correct expectations prevent bugs.
