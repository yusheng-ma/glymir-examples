# ex100_fifo — Synchronous FIFO

> The smallest end-to-end Glymir demo. ~3 minutes from spec dialogue to coverage report.

## What it does

A parameterized synchronous FIFO with `empty` / `full` / `almost_empty` / `almost_full` flags. Single clock domain, configurable depth and width. The smallest design where the full Glymir loop (test plan → testbench → assertions → coverage → weight tuning) has something meaningful to do without RTL complexity getting in the way.

## Status

🚧 RTL + testbench coming. This README is the placeholder.

## Coverage targets (planned)

- Line: ≥ 95%
- Functional: `empty` / `full` / `wraparound` / `burst_write` / `underflow_attempt` / `overflow_attempt`
- Assertion families: write-while-full guard, read-while-empty guard, count integrity

## Try it (when ready)

Open in [Glymir Playground →](#?example=ex100_fifo) — link pending Playground launch.

## Why this example

Pedagogical: FIFOs are the "hello world" of RTL verification. Every IC designer knows the spec; that lets the demo focus on the **workflow** (what an AI agent does for you across multi-skill silos) instead of the **design** (what a FIFO is).
