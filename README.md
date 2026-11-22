# Gongola ICT Hub Website

Public-facing institutional website for Gongola ICT Hub.

## Files
- `index.html`: the website homepage.
- `README.md`: this guide.

## Local preview
Open `index.html` in a web browser. The site uses a Tailwind CSS CDN and requires internet access for that styling.

## Publishing
This website is intended for GitHub Pages. In the public website repository, select **Settings → Pages → Deploy from a branch → main → /(root)**.

After a change, commit it to `main` and check the GitHub Pages deployment status. If the live page is unchanged, inspect the deployment before assuming it is a browser-cache issue.

## Editing
Update text, links, and styling in `index.html`. Test desktop and mobile navigation before committing. No package manager or build command is required.

## Content guidelines
Describe the product accurately. Gongola Terminal currently supports research on XAU/USD and BTC/USD using 5M and 15M charts. Do not describe research outputs as verified trade signals.

## Security
This repository is for public website assets only. Do not add credentials, private source code, internal documentation, or confidential business data. Keep secrets in the appropriate deployment platform's secret storage, never in Git.
