# 🏗️ Archie Technology

Welcome to the official GitHub organization for **Archie Technology** — a collective of builders, thinkers, and dreamers working on modern digital products.

---

## 🎨 Design Files (Figma)

All of our UI/UX and branding work lives in Figma. Here are some key files:

- 🧱 [Aeongang Design System](https://www.figma.com/board/zoQyZdHrHgWgvdl0qTsdEd/AEON-Gang-Flow--Copy-?node-id=0-1&t=qR0Hhe2E7tWC5jin-1) – base components and guidelines  
- 📱 [Aeongang Mobile & Desktop App UI](https://www.figma.com/design/u1KM1FnhSuXXfoHDA96CLQ/AEON-Gang-Design--Copy-?node-id=309-3167&t=IhOPei0fcz9qf038-1) – full mobile and desktop  

> Don’t have access? Ask in Slack or message the project lead.

---

## 🧰 Projects Overview

Here’s a high-level view of our current repos and how to get started with them:

| Project | Description | Tech Stack | Getting Started |
|--------|-------------|------------|-----------------|
| [aeongang web-frontend](https://github.com/archie-technology/aeongang) | Main website | React, Vite, Tailwind | `npm install && npm run dev` |

---

## 📦 Tech Stack & Tools

We typically use:

- React / Next.js / React Native
- Tailwind CSS
- Node.js + Express
- Prisma / PostgreSQL
- GitHub Projects + Issues
- Figma for UI/UX

---

## 🚀 How to Contribute

Want to contribute to a project? Awesome. Here’s the flow:


1. **Clone** it locally and create a feature branch


## 🌿 Branch Naming Convention

To keep our development process clean and collaborative, we follow a consistent naming convention for all branches:

### 📌 Format

- `type` – describes the purpose of the branch
- `short-description` – a brief summary of the work (use kebab-case)

---

### 🏷️ Common Types

| Type         | Use For                                           | Example                               |
|--------------|---------------------------------------------------|----------------------------------------|
| `feature/`   | New features or functionality                     | `feature/login-form`                   |
| `fix/`       | Bug fixes                                         | `fix/user-auth-error`                  |
| `chore/`     | Non-user-facing tasks (e.g., setup, config)       | `chore/update-eslint-config`           |
| `docs/`      | Documentation updates                             | `docs/api-readme`                      |
| `hotfix/`    | Urgent production fixes                           | `hotfix/crash-on-launch`               |
| `refactor/`  | Code improvements without changing behavior       | `refactor/form-validation`             |
| `test/`      | Adding or fixing tests                            | `test/add-login-tests`                 |

---

### 💡 Bonus Tips

- Use **kebab-case** for readability: `feature/add-payment-gateway`
- Reference issue numbers if relevant: `fix/#42-profile-save-bug`
- Keep it short but descriptive
- Always branch off from `dev` (unless it's a `hotfix/`)

---

### ✅ Examples in Context

Let's say you're working on a few different tasks:

| Task                                   | Good Branch Name                     |
|----------------------------------------|---------------------------------------|
| Add a new profile settings page        | `feature/profile-settings`            |
| Fix an alignment bug in user cards     | `fix/user-card-alignment`             |
| Clean up validation logic              | `refactor/validation-helpers`         |
| Add documentation for the API routes   | `docs/api-route-guide`                |
| Urgent crash fix after deploy          | `hotfix/fix-null-ref-error`           |

---

## 📝 Conventional Commits

We use **Conventional Commits** to keep commit messages readable and automated tools effective (e.g., changelogs, semantic versioning).

### 📌 Format


### ✅ Example Commit

| Type       | Purpose                                 | Example                                   |
|------------|------------------------------------------|-------------------------------------------|
| `feat`     | A new feature                            | `feat(auth): add login endpoint`          |
| `fix`      | A bug fix                                | `fix(ui): resolve modal close bug`        |
| `chore`    | Build tasks, dependencies, configs       | `chore: update Tailwind to v3`            |
| `docs`     | Documentation changes                    | `docs(readme): add install instructions`  |
| `refactor` | Code changes without behavior change     | `refactor: simplify validation utils`     |
| `test`     | Adding or fixing tests                   | `test(api): improve coverage for /users`  |
| `style`    | Formatting, semicolons, etc. (no logic)  | `style: format with Prettier`             |

---

### 💡 Tips

- Keep the **summary under 72 characters**
- Use the **imperative mood** (“add” not “added”)
- Scope is optional but helpful: `feat(ui): ...`

---



Stick to these conventions so we all stay on the same page 🚀







---

## 🧃 Archie Tech Jargon Glossary

A mix of serious terms and our team’s inside lingo. Some of these are legit process terms, others are just pure chaos and ✨vibes✨.

| Term              | Meaning                                                                                   | Type            |
|-------------------|--------------------------------------------------------------------------------------------|------------------|
| **FOC**           | First Order Change — small, safe update that won’t break anything.                        | ✅ Official       |
| **ZAP**           | Zero-Asset Push — deploy without extra files, assets, or surprises.                       | ✅ Official       |
| **Design-Locked** | Figma is final and ready to dev. No more tweaks, no more "just one more icon".            | ✅ Official       |
| **Dev-Ready**     | Fully scoped, designed, has acceptance criteria. You may now code.                        | ✅ Official       |
| **Hotfix Mode**   | 🔥 All hands on deck. We’re fixing a prod bug NOW. Skip the dev branch.                   | ✅ Official       |
| **Lint Rage**     | When Prettier or ESLint gaslights you for 20 minutes.                                     | 😂 Vibes         |
| **Shadow Deploy** | Deploy quietly to staging without telling anyone... for QA ninjas only. 🥷                | ✅ Official       |
| **Smoke Test**    | Quick test to make sure nothing exploded.                                                 | ✅ Official       |
| **Reflow**        | When the layout shifts like jelly. Usually caused by CSS or image loading.                | ✅ Official       |
| **Dev Freeze**    | No more merges! Only critical bugs allowed. Don’t even think about pushing. ❄️            | ✅ Official       |
| **Confetti Push** | You just finished something major — deploy and drop some 🎉 in Slack.                     | 🎉 Vibes         |
| **🫠 Tuesday**     | When you push on Monday and QA finds 7 bugs by Tuesday.                                   | 😵‍💫 Just Vibes   |
| **Scope Creep**   | When the “small tweak” becomes a full rework. “It’s just one button…” 🫣                  | ✅ Official (sadly) |
| **Figma Fog**     | That moment you forget what frame you were editing.                                       | 🤷‍♀️ Designer Vibes |
| **Rubber Ducking**| Talking to a teammate or a literal rubber duck to debug your logic. It actually works. 🦆 | ✅ Official (and effective) |

---

> Want to add your own? PR to this section or drop your best lingo in `#jargon-ideas` 🧃

