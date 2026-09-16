# AI Engineering Skills & Rules Workspace 🧠⚙️

A centralized workspace and hub for professional, production-grade AI coding agent skills, Cursor rules, and prompt constraints authored by **Saddam Al-Slfi**.

Each sub-directory is an **independent, standalone project** with its own Git repository, Open Plugins specification, and metadata, ready for distribution to [cursor.directory](https://cursor.directory), [LangChain Hub](https://smith.langchain.com/hub), and the [Open Plugins Registry](https://open-plugins.com).

---

## 📂 Projects & Standalone Repositories

```text
G:\SwiftEx\Skills\
├── laravel-skills-localsetup/     # Standalone Repo: Laravel 13 Local Development Setup
│   ├── skills/laravel-skills-localsetup/SKILL.md
│   ├── rules/laravel-skills-localsetup.mdc
│   ├── plugin.json
│   ├── mcp.json
│   ├── README.md
│   └── LICENSE
│
└── laravel-skills-multilingual/   # Standalone Repo: Laravel Multilingual & Localization
    ├── skills/laravel-multilingual/SKILL.md
    ├── rules/laravel-multilingual.mdc
    ├── plugin.json
    ├── mcp.json
    ├── README.md
    └── LICENSE
```

---

## 📦 Projects Catalog

### 1. [Laravel 13 Local Development Setup (`laravel-skills-localsetup`)](./laravel-skills-localsetup)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22781072.svg)](https://doi.org/10.5281/zenodo.22781072)
* **Goal:** Deterministic, end-to-end local environment setup for **Laravel 13.x**.
* **Features:** Host vs. WSL2 pre-flight detection, Livewire Single-File Components (SFC), Team support, full authentication suite (2FA, passkeys, verification), AI coding guidelines, and deterministic health checks.
* **Cursor Rule:** [`rules/laravel-skills-localsetup.mdc`](./laravel-skills-localsetup/rules/laravel-skills-localsetup.mdc)
* **Agent Skill:** [`skills/laravel-skills-localsetup/SKILL.md`](./laravel-skills-localsetup/skills/laravel-skills-localsetup/SKILL.md)

### 2. [Laravel Multilingual Implementation (`laravel-skills-multilingual`)](./laravel-skills-multilingual)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22781033.svg)](https://doi.org/10.5281/zenodo.22781033)
* **Goal:** Full-lifecycle internationalization (i18n) and localization (L10n) in Laravel.
* **Features:** Public website locale routing and SEO canonical redirects via `mcamara/laravel-localization`, strict Filament admin panel isolation, JSON-backed Eloquent translations (`spatie/laravel-translatable`), and queue worker locale reset safety.
* **Cursor Rule:** [`rules/laravel-multilingual.mdc`](./laravel-skills-multilingual/rules/laravel-multilingual.mdc)
* **Agent Skill:** [`skills/laravel-multilingual/SKILL.md`](./laravel-skills-multilingual/skills/laravel-multilingual/SKILL.md)

---

## 📄 License & Ownership

Authored by **Saddam Al-Slfi** ([@saddamalsalfi](https://github.com/saddamalsalfi)).

All projects in this workspace are licensed under the **[MIT License](LICENSE)** with an explicit **Special Grant for Artificial Intelligence (AI) Agents & Automated Systems**.