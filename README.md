# glymir-examples

Examples for the **Glymir** agentic DV suite — MediaTek Research's natural-language AI agents for IC design test-driven development.

> *"You only know what you want in the end. AI-assisted TDD helps you get to the end."*

## What is this

A catalog of reproducible examples showing how Glymir agents drive incremental TDD for silicon — test plan generation, testbench, assertions, coverage closure, weight tuning — all via natural-language dialogues.

Each example is runnable in browser via the [Glymir Playground](#) (link TBD) or end-to-end on Colab.

## Examples

| Name | Description | Complexity | Status |
|---|---|---|---|
| [ex100_fifo](./ex100_fifo) | Synchronous FIFO | ⭐ | 🚧 WIP |
| ex200_axilite | AXI-Lite slave | ⭐⭐ | 📋 Planned |
| ex300_alu_ref | ALU with reference model | ⭐⭐ | 📋 Planned |
| ex500_riscv_simple | RISC-V simple pipeline | ⭐⭐⭐ | 📋 Planned |
| ex600_cva6 | CVA6 RISC-V core | ⭐⭐⭐⭐ | 📋 Planned |

## Where to start

The fastest path is [`ex100_fifo`](./ex100_fifo) — minimal design, ~3 minutes end-to-end.

## Try in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](#) &nbsp; *(notebook coming soon — link will swap in when the public Colab is published.)*

The Colab path bundles Verilator + the Advisor binary + sample designs; you can run the full Advisor → CloudSim → Find loop in a browser tab without installing anything locally.

## Contributing

See [`_template/`](./_template) for the example structure. PRs welcome.

## Links

- Glymir Playground — *coming soon*
- [MediaTek Research](https://www.mtkresearch.com/) — contact: info@mtkresearch.com
