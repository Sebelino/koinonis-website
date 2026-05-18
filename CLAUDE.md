# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Static website for koinonis.com — a single-page site hosted on GitHub Pages with a custom domain (configured via `CNAME`).

## Architecture

- `index.html` — the entire site (HTML + inline CSS, no JavaScript, no build step)
- `CNAME` — GitHub Pages custom domain configuration pointing to `koinonis.com`

## Development

No build tools, package manager, or dependencies. Open `index.html` in a browser to preview locally.

## Deployment

Pushes to `main` are deployed automatically via GitHub Pages.
