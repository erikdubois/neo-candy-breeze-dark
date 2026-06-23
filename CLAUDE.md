# CLAUDE.md — neo-candy-breeze-dark

## Project overview

Standalone repo for the **neo-candy-breeze-dark** folder-icon theme — the same folder set as
`erikdubois/surfn-breeze-dark` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-breeze-dark/` — folders only. Packaged as `neo-candy-breeze-dark-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-breeze-dark/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
