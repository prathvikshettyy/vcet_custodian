# Contributing to Custodian

Thank you for your interest in contributing to **Custodian: Culture on Its Own Terms**.

Custodian is a community-owned cultural preservation platform. All contributions must respect cultural authority, provenance, and community consent.

---

## 📜 Cultural Preservation Standards

1. **Prior Informed Consent:** Never submit audio, photographic, or written records of traditional lore without explicit consent from hereditary knowledge holders or community councils.
2. **Respect Custodian Boundaries:** If an elder or guild designates a ritual, prayer, or technique as private or confidential, it must be protected under a `custodianBoundary` object or excluded entirely.
3. **Linguistic Fidelity:** Preserve indigenous phonetic spellings and dialects. Do not standardize or anglicize regional vocabulary.

---

## 💻 Development Workflow

### Setup
```bash
# Clone the repository
git clone https://github.com/prathvikshettyy/vcet_custodian.git
cd vcet_custodian

# Install dependencies
npm install

# Start development server
npm run dev
```

### Building & Testing
```bash
# Run linter
npm run lint

# Build production bundle
npm run build

# Preview build locally
npm run preview
```

---

## 🎨 Design System Guidelines

* **Parchment Surface Foundation (80%):** Use `--color-paper-50` for page background and `--color-paper-100` for panels.
* **Ink Hierarchy (15%):** Use `--color-ink-900` for primary headings, `--color-ink-700` for body copy, and `--color-ink-500` for metadata.
* **Terracotta Accent (5%):** Use `--color-terracotta` exclusively for primary action triggers and active waypoints.
* **Typography:**
  * Display & Headings: `Cormorant Garamond` (serif).
  * UI & Narrative Body: `Inter` (sans-serif).

---

## 📦 Commit Message Conventions

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

* `feat(...)`: New user-facing capability or component
* `fix(...)`: Bug fix
* `refactor(...)`: Code cleanup or restructuring without feature changes
* `style(...)`: CSS tokens, formatting, or styling updates
* `docs(...)`: Documentation additions or revisions
* `chore(...)`: Tooling, build config, or dependency changes
