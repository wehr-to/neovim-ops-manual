# neovim-ops-manual

- This repo documents my process of learning and configuring Neovim for use in security engineering workflows. It’s meant to serve as a personal knowledge base, reference toolkit, and example of terminal-first proficiency.

### Why Neovim?

In security work — especially on Linux systems, hardened servers, remote boxes, or during incident response — graphical interfaces are often unavailable or impractical. Learning Neovim ensures I can:
- Edit and audit system configurations securely over SSH
- Navigate logs quickly during investigations
- Work efficiently in low-resource, CLI-only environments
- Avoid relying on GUIs when assessing or hardening remote infrastructure

Neovim is lightweight, customizable, and designed for control over convenience, which aligns well with security operations and infrastructure work.

---

### What's in This Repo

This is not a general-purpose Neovim guide. Everything here is focused on practical, security-relevant use cases.

├── 01-getting-started/ # Basics and setup
├── 02-core-config/ # My init.lua, plugin choices, and theme setup
├── 03-terminal-workflows/ # SSH, tmux, fzf, productivity workflows
├── 04-use-cases/ # Log analysis, config hardening, scripting
├── 05-learning-path/ # Neovim vs VS Code, next steps


- Each section is written from the lens of someone building real-world security and automation skills — not chasing aesthetics or hype.

---

### Who This Is For

- Anyone in security or DevOps roles working in terminal-first environments
- Students and professionals preparing for blue team, systems, or IR work
- Engineers looking to deepen their tool fluency and minimize reliance on GUIs

---

### License

MIT — use, fork, adapt.
