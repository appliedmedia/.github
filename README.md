<img
  src="/assets/logo-appliedmedia-bright-bg.svg"
  alt="Applied Media logo"
  width="300"
/>

## Applied Media - Organization Infrastructure

This repository contains organization-wide public resources for Applied Media projects.

## Repository Structure

```
.github/
├── scripts/             # Cross-project automation scripts
├── profile/             # Organization profile (shows on github.com/appliedmedia)
│   └── README.md
└── .github/
    └── workflows/       # Shared GitHub Actions workflows
```

## Scripts

### `scripts/enable-github-pages.sh`
Enables GitHub Pages and configures CNAME files for all Applied Media web presence repositories.

**Usage:**
```bash
export GH_TOKEN=$(gh auth token)
./scripts/enable-github-pages.sh
```

## Applied Media Projects

- [print2paper4vscode](https://github.com/appliedmedia/print2paper4vscode) - VS Code extension for printing code
- [gmail2trello](https://github.com/appliedmedia/gmail2trello) - Chrome extension for email to Trello
- [print2paper4vscode.com](https://github.com/appliedmedia/print2paper4vscode.com) - Marketing site for Print2Paper4VSCode
- [gmail2trello.com](https://github.com/appliedmedia/gmail2trello.com) - Marketing site for gmail2trello
- [cov.llc](https://github.com/appliedmedia/cov.llc) - Fractional CTO consulting site

---

🇺🇸 Made in the USA by Applied Media
