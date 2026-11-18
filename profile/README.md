# Stream Does Research

Clean-room reverse engineering, binary format specifications, and portable decompilation tooling for classic console software.

## What We Publish

- **Clean-Room C Rewrites & Headers:** Human-readable C modules, typed ABI structs, and memory maps documented from scratch without distributing proprietary code.
- **Container & Save Decoders:** Pure-stdlib Python tools for inspecting game archives, sound banks, sprite sheets, and save formats with deterministic offline test fixtures.
- **Portable `.decomp` Bundles:** Self-contained schema and script packages built for downstream static recompilation engines.

## Public Repositories

| Repository | Platform | Scope |
| :--- | :--- | :--- |
| [MeadowValley-BackToEarth-SlateOne-04-Decomp](https://github.com/StreamResearch/MeadowValley-BackToEarth-SlateOne-04-Decomp) | SlateOne / MIPS32 (`SLUS-01115`) | Clean-room C rewrite, container decoders, format specifications, and `.decomp` bundle |

## Clean-Room & Bring-Your-Own-Media Policy

Repositories under `StreamResearch` contain **zero** copyrighted disc images, ROMs, BIOS dumps, retail binaries, textures, audio, or extracted game assets. Verification suites run offline against synthetic test fixtures, and unpacking tools validate user-supplied media locally via cryptographic checksums.

- **Security & Leak Reporting:** Use the **Security Advisories** tab on the relevant repository rather than opening a public issue.
- **Links:** [Linktree](https://linktr.ee/streamitall)