# Bash Scripting & System Administration Guide

Personal reference for shell operations, batch management, Glow navigation, and environment rules.

---

## 1. Directory Structure Rules & Best Practices

* **Container Folder:** Keep all project repositories inside a global container directory (e.g., `~/GitHub/`).
* **Git Isolation:** Never run `git init` inside `~/GitHub/` directly. Each project subfolder contains its own hidden `.git` folder tracking its history independently.
* **Relative Links:** Use relative paths (e.g., `./bash/bash.md`) inside Markdown files so links work seamlessly across GitHub's browser interface and local tools.

---
---
---
## 2. Terminal Markdown Viewer (`glow`)

Use `glow` to read formatted Markdown directly in your terminal without opening a GUI editor or text viewer.

```bash
# Render the primary notebook menu
glow README.md

# Render this Bash reference directly
glow bash/bash.md
