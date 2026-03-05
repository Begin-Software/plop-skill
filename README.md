# plop-skill

A [Claude Code skill](https://code.claude.com/docs/en/skills) that lets Claude upload files to [plop.so](https://plop.so) and get permanent public URLs.

Plop is a file hosting service — upload any file, get a permanent link. Supports custom domains and subdomain aliases.

## Install

```bash
git clone https://github.com/ccarse/plop-skill.git ~/.claude/skills/plop-upload
```

## What's included

- **SKILL.md** — Auth + upload (always loaded)
- **claim.md** — Claim a subdomain (loaded on demand)
- **domains.md** — Manage custom domains (loaded on demand)

## Auth

Requires a token at `~/.plop/config.json`. The skill includes device-code OAuth instructions for logging in if no token exists.
