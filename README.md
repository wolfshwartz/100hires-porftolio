# AI Coding Tools Setup

Documentation of my setup of Cursor IDE with the Claude Code and Codex extensions, completed as the first step of the HundredHires portfolio process.

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

<!--
Replace the examples below with the issues YOU actually hit. Be specific —
mention the exact message or behavior and the exact thing that fixed it.
If something genuinely went smoothly, say so honestly rather than inventing a problem.
Delete any that don't apply to you.
-->

- **Authenticating the extensions.** After installing each extension, I had to complete a separate sign-in (browser-based OAuth) before it would work — installing the extension alone wasn't enough. Solved by clicking the sign-in prompt in the extension panel and approving access in the browser, then returning to Cursor.
- **Telling the two assistants apart.** Claude Code and Codex both add their own panel/commands, so it took a moment to confirm each was active and logged in independently. I verified each by opening its panel and checking it showed a connected/signed-in state.
- **First push to GitHub.** [Describe what happened — e.g. needed to set the remote, authenticate with a Personal Access Token instead of a password, or set the default branch to `main`. State exactly what you did.]

## What I Learned

Setting up an AI-native editor is mostly about getting each tool authenticated correctly rather than the install itself. The editor, the assistants, and GitHub are three separate accounts that each need their own sign-in, and the workflow only clicks once all three are connected.

---

*Setup completed on [DATE]. Repository created and pushed to GitHub as part of the HundredHires application process.*
