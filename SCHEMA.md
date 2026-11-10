# vicki schema

Public demo of the LLM Wiki pattern. This file describes how the wiki is structured and how to keep it consistent.

## Where

- Path: repository root
- Machine: demo

## Layout

- `raw/` — sanitized immutable captures
- `wiki/` — compiled markdown pages and the static diagram
- `notes/` — placeholder; private notes stay out
- `experiments/` — placeholder; experiment work stays out
- `index.html` — interactive route map
- `index.md` — content-oriented wiki index
- `SCHEMA.md` — this schema
- `AGENTS.md` — local path map for the HULK catalog

## Edit

- `wiki/` pages are compiled; update them when a source changes.
- `raw/` is immutable; add a new capture instead of editing an old one.
- `index.md` gets a line when a page or source is added.
- Sanitize before publishing: no usernames, local IPs, MACs, SSIDs, device paths, secrets, or private notes.

## Leave alone

- Private source data, notes, experiments, weights, environments, and secrets.
