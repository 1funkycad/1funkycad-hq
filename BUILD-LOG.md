# BUILD LOG — 1FunkyCAD HQ

Newest first. Every agent that changes something logs it here: date, what changed, how it was verified.

## 2026-11-23

- Repository `1funkycad/1funkycad-hq` created as the shared source of truth and workspace for HQ, with README.md (what the site is), AGENT-BRIEF.md (brand rules, art direction, privacy rules, improvement backlog, Ghostboy music rules, review & culling rules, how to contribute) and this build log.
- The standing iterator is the **Friday HQ loop** (cron `hq-media-weekly`, owned by the 1FunkyCAD Media Studio goal): each Friday it takes the highest unblocked item from the improvement backlog in AGENT-BRIEF.md, builds it into the live site, verifies it (screenshot + control inventory at desktop and phone widths), and logs the result here.
