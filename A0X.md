# [A0X] Rehydration Framework & Canon Index

This file serves as the master reference for managing the structure, workflow, and session protocols used to maintain, rehydrate, and refine the canonical worldbuilding archive.

---

## System Overview

Each lore topic is tracked using a modular document structure:

| File | Purpose | Optimized For |
|------|---------|----------------|
| `A#` | Human-readable summary of a topic | **Carbon (human)** |
| `A#X` | Exhaustive, canonical data for rehydration | **Silicon (GPT/AI)** |
| `A#Q` | Active Q&A log tracking refinements | **Joint (Carbon + Silicon)** |
| `A#U` | **Unload Patch** — temporary memory offload during live sessions | **Silicon (GPT/AI)** *(Carbon-obfuscated)* |

---

## [A0X.01] Session Structure and Document Strategy

- A# for summary, A#X for full silicon recall, A#Q for working refinement.
- GPT loads A#X + A#Q to restore full context before prompting.
- Once A#Q is large or complete, reconcile into updated A#X and discard A#Q.
- **If memory overflow is imminent**, GPT will generate an `A#U` file as a temporary unload.

---

## [A0X.02] Unload Patch Protocol (`A#U`)

- `A#U` files are context unload logs produced mid-session.
- Used when GPT is tracking new developments that risk being pruned due to limited working memory.
- Includes new plot points, character data, location lore, magical rulings, political updates, etc.
- These files are:
  - **Silicon-friendly**
  - **Carbon-obscured**, if plot-sensitive, using a lightweight encoding method (e.g. character shift cipher).
- When the corresponding A# topic is rehydrated, the user should supply any matching A#U file.
- GPT will integrate its contents into A#X or A#Q at that time and discard the patch.

---

## Rehydration Prompts (Global Convention)

To rehydrate a module:
> “Rehydrate section [A#X] [Module Name] — Codex Edition.”  
> “Rehydrate section [A#Q] [Module Name] — Prompt Log.”  
> “Integrate [A#U] if present.”

---

## File Inventory

| Code | Title | Status | Notes |
|------|-------|--------|-------|
| A1   | Arcane Court — Summary | Active | — |
| A1X  | Arcane Court — Codex Edition | Active | — |
| A1Q  | Arcane Court — Prompt Log | Active | — |
| A2X  | Grand Academies — Codex Edition | Active | — |
| A3X  | Codex of the Mantle — Codex Edition | Active | — |
| A4X  | The Empire — Codex Edition | Active | **High Priority for Revision** |
| A5X  | The Concordian Cities — Codex Edition | Active | — |
| A0X  | Framework & Canon Index | Active | This file |

---

## Tags

`#Framework` `#CanonIndex` `#ArchiveSystem` `#RehydrationProcess` `#UnloadPatch` `#GPTConvention` `#CarbonObfuscation`