# AGENTS.md

This file tells AI coding agents (Claude Code, Copilot, Cursor, Codex, etc.) how to work in this repository. It is written for an **Applied Programming** course project: a web or mobile app designed and built by a student. Agents must follow these rules for every change, large or small.

> **Students:** Fill in the "Project Details" section below before you start using agents. The more specific you are, the better your agent will follow your architecture.

---

## 1. Project Details (student fills this in)

- **App name:** Portfolio_Website
- **One-sentence description:** An online portfolio that will showcase the projects that I have done.
- **Project Requirements** 
Write a web app using one of the following frameworks:

    Django - Python

    Node - Javascript

    React - Javascript

The web app must have the following characteristics:

    Must have at least two HTML pages populated by content determined by your Python (Django) or JavaScript (NodeJS) code. However, if you use React, then you can keep to a single page with multiple interactions.

    Your software must be interactive meaning that the content displayed in your web app must be in some part based on user input.

    The web app should run on your local computer using the test server provided by your framework.

Use the Web App README.md template.
- **Platform:** Web
- **Language(s):** Python
- **Frameworks:** Django
- **Data storage:** local device storage
- **Test framework(s):** I don't know yet
- **Command to run the app:**
- **Command to run all tests:**
- **Command to run a single test file:**
- **Command to run the linter/formatter:**

---

## 2. How Agents Should Behave in This Project

This is a learning environment. The student is responsible for understanding every line of code in the project. Agents must support that.

1. **Work in small steps.** Make one focused change at a time. Prefer several small, reviewable changes over one large one.
2. **Explain your reasoning.** After each change, briefly state what you changed, which layer it belongs to, and why.
3. **Ask before big decisions.** Adding a new dependency, changing the database schema, restructuring folders, or introducing a new pattern requires the student's approval first.
4. **Do not invent requirements.** If behavior is unclear, ask the student instead of guessing.
5. **Never hide failures.** If tests fail, a command errors, or you are unsure something works, say so plainly.
6. **Keep secrets out of code.** API keys, passwords, and tokens go in environment variables or config files that are excluded by `.gitignore`. Never commit them.

---

## 3. What to do if you find inconsistencies

This AGENTS.md was modified from another project to fit this project. If there are any inconsistencies within this document, please ask the student for clarification.