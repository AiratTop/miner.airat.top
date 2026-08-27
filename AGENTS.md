# AGENTS.md

## Purpose
Public browser Minesweeper game (`miner.airat.top`).

## Repository Role
- Category: `*.airat.top` (public static tool/game).
- Deployment platform: Cloudflare Workers (static assets).
- Deployment configuration: `wrangler.jsonc`.
- Main content directory: `public_html`.

## Content and Structure
- Main page: `public_html/index.html`.
- Game assets/styles/scripts are in `public_html`.

## Site Conventions
- Keep UI consistent with AiratTop tool ecosystem while preserving game-specific UX.
- Keep SEO metadata and social tags in `index.html`.
- Keep the Google Analytics counter and other required site-verification tags.
- Publish static assets from `public_html`.

## AI Working Notes
- Preserve game mechanics and difficulty behavior.
- Prioritize responsive/mobile-friendly controls when editing layout.
