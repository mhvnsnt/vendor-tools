# HANDOFF — vendor-tools

**Last updated: 2026-11-22 (America/New_York).**
**Repo:** `mhvnsnt/vendor-tools` (PUBLIC), default branch `main`.
**Purpose of this file:** any agent that picks up work here reads this FIRST, then the linked docs. It states what we've done, where we're at, and what we're working toward — so the owner can say "go to this repo, pick up the work" and you just know. Update this file in the same PR whenever the state changes (add, don't delete).

## 1. What this repo is

Vendor software tools: re-downloadable binaries stored as release assets, with version/source docs. The point is never being stuck re-hunting a vendor download: the binary lives here as a release asset, with where it came from written down next to it. Small repo (~7 KB of code/docs on main; the bulk is in releases).

Current contents: `cascadeur/` — Cascadeur 2026.2.3 Linux, free Basic tier, direct-download documented (`bfbc90c`, 2026-10-18). `AGENTS.md`, `WORKING-METHOD.md`, `README.md` at the root.

## 2. Where we're at

### DONE
- **Cascadeur 2026.2.3 Linux (2026-10-18, PR #2 merged):** free Basic tier, direct download, version/source doc in `cascadeur/README.md`.
- **Release vendor-tools-v1 (2026-10-16):** the first release asset set.
- **Working method statement (2026-10-27):** `WORKING-METHOD.md` landed.

### IN PROGRESS
- Nothing is actively in progress in this repo that the repo itself records. Last push was the 2026-10-27 sweep commit (via the 2026-11-20 push batch).
- **PRE-MADE PARTS FIRST rule (open PR #3).** Standing-rule PR, unmerged.

### BLOCKED
- Nothing recorded as blocked in this repo.

## 3. What we're working toward

Every vendor tool the lanes depend on, stored here with its version and source — so a rebuild never starts with a dead download link. The bar: each tool has its binary as a release asset AND its version/source written down; a tool with no source note does not count as stored.

## 4. Standing rules that apply here

- **Branch → PR → merge, always.** Never push to main directly. Add-only, zero-conflict PRs, no force pushes.
- **Checkpoint-and-save law:** CHECKPOINT.md first, update after every step; the repo is the save; resume, never restart.
- **No-temp-storage law:** nothing in /tmp or any wipeable location, ever.
- **Licence-not-a-gate:** licence status never blocks pulling in or using material that helps — licence/source is still logged honestly next to the item.
- **Paid-tool equivalents:** find the free top-level industry-standard equivalent first; never bring the owner a purchase list.
- **Never kill in-progress work.**

## 5. Key files and paths

| What | Where |
|---|---|
| Cascadeur 2026.2.3 | `cascadeur/` (incl. `cascadeur/README.md`) |
| Agent rules | `AGENTS.md` |
| Method doc | `WORKING-METHOD.md` |
| Releases | `vendor-tools-v1` (2026-10-16) |
| Open PR | #3 (PRE-MADE PARTS FIRST rule) |

## 6. Open decisions needing the owner

- **Next vendor tools to store:** which tools get added next is his call — lanes do not pick the list.
- No other decisions are recorded in this repo.

## 7. How to pick up

1. Read this HANDOFF.md first, then `README.md` and `WORKING-METHOD.md`.
2. Check the releases to see what is actually stored before adding anything (never store a duplicate blind).
3. Check what other agents are already doing before starting anything.
4. Resume from the stated next step — never restart, never re-derive finished work.
5. Land work branch → PR → merge, add-only. Log version + source next to every tool added.
6. Update this HANDOFF.md in the same PR when the state changes. Verify with your own eyes before claiming anything stored.
