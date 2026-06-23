# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

No build step. Pure static HTML/CSS/JS — open files directly or serve with any static file server:

```bash
npx serve .    # serve locally if needed
```

## Architecture

**PetVet Website** — static marketing site for the PetVet platform (petvet.org.za). No framework, no build tool.

### Files

```
index.html      # main landing page
privacy.html    # privacy policy
popia.html      # POPIA compliance page
terms.html      # terms of service
```

All styles and scripts are inline within each HTML file. Google Fonts loaded via CDN (DM Serif Display, DM Sans, DM Mono). Structured data (Schema.org JSON-LD) is embedded in each page's `<head>`.

No JavaScript framework. Edit HTML directly.
