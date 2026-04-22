# elevate-tools

A Claude Code plugin marketplace bundling Justin Beadle's custom persona skills and utilities for Elevate Consulting.

## Plugins

| Plugin | Skills | Purpose |
|---|---|---|
| `devops-team` | 6 | Product & engineering personas |
| `strategy-team` | 9 | Strategy advisory personas |
| `tiger-team` | 6 | Security / reliability personas |
| `social-services-panel` | 9 | Canadian social services sector personas |
| `medical-ethics-panel` | 6 | BC/Alberta medical ethics personas |
| `dataanalysis-panel` | 9 | Data analysis & ML research personas |
| `utilities` | 2 | Gail (finance) + Humanize (writing) |

**Total:** 47 skills across 7 plugins.

## For colleagues on individual Claude.ai accounts (no Claude Code)

If your colleagues use only claude.ai (not Claude Code), they can upload each skill as a ZIP through **Settings → Capabilities → Skills → Upload skill**.

Download **`elevate-skills-bundle.zip`** from the latest release, unzip it, and follow **`cowork-import-bundle/START-HERE.md`** for beginner-friendly step-by-step instructions.

## Install (local test)

```
/plugin marketplace add /Users/justinbeadle/Documents/JustinDevOps/2026-04-22_elevate-tools
/plugin install strategy-team@elevate-tools
```

## Install (after pushing to GitHub)

```
/plugin marketplace add <github-owner>/elevate-tools
/plugin install elevate-leadership@elevate-tools
```

## Validate

```
/plugin validate .
```
