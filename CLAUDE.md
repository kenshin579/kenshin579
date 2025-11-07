# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile README repository** (kenshin579/kenshin579). The README.md file in this repository automatically displays on the GitHub profile page at https://github.com/kenshin579.

## File Structure

- **README.md**: The main profile content displayed on GitHub profile page
  - Uses GitHub-flavored markdown with HTML for layout
  - Contains badges from shields.io for tech stack and social links
  - Includes dynamic GitHub stats via github-readme-stats API
  - View counter via hits.seeyoufarm.com

## Updating Profile Content

When modifying README.md:

1. **Badges**: Use shields.io format: `![Label](https://img.shields.io/badge/-Text-333333?style=flat&logo=logoname)`
2. **GitHub Stats**: Stats images are dynamically generated - URLs don't need updating
3. **Sections**: Current structure includes About Me, Tech Stack, GitHub Stats, and Connect sections
4. **Alignment**: Uses `<div align=left>` for consistent left alignment

## Common Tasks

- **Update tech stack**: Modify the badge list under "🛠 Tech Stack" section
- **Update social links**: Modify badge URLs under "🤝🏻 Connect with Me" section
- **Change stats theme**: Modify `theme=buefy` parameter in github-readme-stats URLs
- **Preview changes**: Commit and push to see updates on GitHub profile (no local preview needed)

## Notes

- This repository contains no source code or build system
- Changes to README.md are immediately reflected on the GitHub profile page after push
- Badge logos use simple-icons names (e.g., `logo=python`, `logo=kubernetes`)
