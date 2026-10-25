[English](AGENTS.md) | [日本語](AGENTS.ja.md)

# Working instructions

This folder contains a proposed public-facing repository package. It is separate from the private implementation repository.

## Read and update

- Start with [README.md](README.md), then choose [English](README.en.md) or [日本語](README.ja.md), and read this file.
- Keep each English document paired with its `.ja.md` counterpart. Put language links at the top of both pages.
- Update the matching pair together. For project intent and status, update `PROJECT_OVERVIEW.md` and `PROJECT_OVERVIEW.ja.md`, plus `NOW.md` and `NOW.ja.md`.
- For thesis edits, update `MANIFESTO.md` and `MANIFESTO.ja.md`; preserve the distinction between the recovered source note and later editorial versions.
- For publications, copy a language-specific template under `templates/` and link the resulting report from both README language pages when appropriate.
- For disclosure decisions, update both `DISCLOSURE_POLICY.md` and `DISCLOSURE_POLICY.ja.md`. Do not copy private implementation details into this folder.

## Before changing public material

Check all affected text and artifacts for secrets, personal data, confidential details, unsupported claims, and incorrect status labels. Mark ideas as hypotheses, prototypes as prototypes, and results with their method and limitations. Do not imply that the product is complete or validated without evidence.

## Repository boundary

Keep this public package separate from private implementation. Do not create remotes, push, or change repository visibility as part of routine editing. Public release requires the owner to review the concrete contents first.
