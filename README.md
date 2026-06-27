# AI Coding Tools Setup

Documentation of my setup of Cursor IDE with the Claude Code and Codex extensions, completed as the first step of the 100Hires portfolio process.

## Tools Installed

- **Cursor IDE** — AI-native code editor (a fork of VS Code) used as the working environment. Downloaded from https://cursor.com/
- **Claude Code** — Anthropic's agentic coding assistant, added as a Cursor extension and signed in.
- **Codex** — OpenAI's coding assistant, added as a Cursor extension and signed in.

## Steps Completed

1. Downloaded and installed Cursor IDE on my MacBook.
2. Opened Cursor and signed in to my account.
3. Opened the Extensions panel, searched for **Claude Code**, installed it, and logged in.
4. Opened the Extensions panel, searched for **Codex**, installed it, and logged in.
5. Created a new **public** GitHub repository for this project.
6. Cloned / opened the repository in Cursor.
7. Created this `README.md` file documenting the setup.
8. Committed the change and pushed it to GitHub.

## Issues I Ran Into and How I Solved Them

The setup ran smoothly end to end. The install steps were straightforward and neither extension required a separate browser-based OAuth sign-in as I already connected my account with VScode — installing each one and confirming it was active in the Extensions panel was enough to get it working.

The one thing I made sure of was verifying each tool independently rather than assuming it was ready: I opened both the Claude Code and Codex panels to confirm each was installed and active, and double-checked the GitHub repository was set to public before pushing.

One thing I discovered was that editing the README locally does not automatically update GitHub. Every time I made a change, I had to run `git add`, `git commit`, and `git push` in the terminal to sync the changes. Once I understood this workflow, I made it a habit to push after every edit so the repository always reflects the latest version.

## What I Learned

Setting up an AI-native editor turned out to be more straightforward than expected — the install and extension steps were quick and didn't require extra authentication hurdles. The main takeaway was the value of verifying each piece independently: confirming both assistants were active and that the GitHub repo was public, rather than assuming everything was in place.

---

*Setup completed on 06/27/2026. Repository created and pushed to GitHub as part of the 100Hires application process.*
