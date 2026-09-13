# OOT2 Public Feed

Public-safe machine-readable data for the OOT2 master project website.

This repository is intentionally public. It must contain **only sanitized project information** that is safe to display on the public OOT2 website.

## Canonical website

https://oot2-master-project.sudzey.chatgpt.site

## Feed files

- `project.json` - current project phase, progress, status, and headline information.
- `updates.json` - sanitized development updates.
- `github-feed.json` - human-readable engineering activity summaries; never raw private commits.
- `build-status.json` - safe high-level build/test state.
- `roadmap.json` - public roadmap and milestones.
- `gallery.json` - approved gallery metadata only.
- `site-status.json` - whether a ChatGPT Sites republish is required for a structural site change.

## Security rules

Never publish credentials, tokens, emails, personal names, precise locations, IP addresses, machine names, local file paths, ROMs, extracted commercial assets, private-repository URLs/content, raw crash logs, arbitrary desktop screenshots, or unsanitized commit messages.

The private OOT2 repository generates these files through an allowlisted sanitizer. This repository is the **output**, not the source of truth.

Concept images that exceed the current playable build must be labeled exactly:

**Concept Art / Visual Target — Not Gameplay**
