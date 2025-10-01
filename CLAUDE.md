# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Fame Express LLC (www.fameexpress.com), hosted via GitHub Pages. The site showcases portfolio projects and company information.

## Architecture

- **Static HTML site**: No build process, frameworks, or dependencies
- **GitHub Pages hosting**: The CNAME file configures the custom domain
- **Two main pages**:
  - [index.html](index.html): Landing page with project portfolio
  - [privacypolicy.html](privacypolicy.html): Privacy policy page
- **Styling**: Uses external new.css framework (https://newcss.net/new.min.css) for index.html; inline CSS for privacy policy

## Deployment

Changes pushed to the `main` branch are automatically deployed to www.fameexpress.com via GitHub Pages. No build or deployment commands required.

## Editing Workflow

1. Edit HTML files directly
2. Commit and push to `main` branch
3. Site updates automatically via GitHub Pages
