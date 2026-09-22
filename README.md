# Mulungushi University — Course Registration Portal

**Course:** ICT461 — Competency Lab
**Students:** 
GROUP A MEMBERS
S/N	STUDENT NAME	STUDENT NUMBER
1	NGOSA SUSAN	202307058
2	CHIRWA JOYCE	202303607
3	TACHILA NYIRENDA	202307097
4	MWANZA ANDREW	202307128
5	SHATUMUKA BUKATA	202307073
6	MIYOKO STUART	202307056
7	TREASAH CHISHIMBA	202304384
8	EMMANUEL CHITUNDU	202304663

**Repository:** `mulungushi-registration`
**Stack:** Node.js + Express (API), vanilla HTML/CSS/JS with ES modules (UI)
**Status:** Lab prototype — in-memory storage only; no database, no real authentication

A small, accessible course-registration portal for Mulungushi University. It
runs on a phone, is fully usable with a keyboard, reports validation errors
clearly, and rejects duplicate registrations. The browser and server
communicate over a documented JSON HTTP contract; caching, CORS and cookies are
demonstrated and inspected in DevTools.

---

## Table of contents

1. [Quick start](#quick-start)
2. [Project structure](#project-structure)
3. [Task 1 — Accessible interface](#task-1--accessible-interface)
4. [Task 2 — HTTP contract](#task-2--http-contract)
5. [Task 3 — Caching and browser boundaries](#task-3--caching-and-browser-boundaries)
6. [Task 4 — State, security and performance](#task-4--state-security-and-performance)
7. [Checkpoint A — System sketch and standards](#checkpoint-a--system-sketch-and-standards)
8. [Checkpoint B — Prediction log](#checkpoint-b--prediction-log)
9. [AI assistance](#ai-assistance)
10. [Evidence index](#evidence-index)
11. [Limitations and design-only failures](#limitations-and-design-only-failures)

---

## Quick start

Prerequisites: Node.js 20+, npm, a modern browser with DevTools, Git.

```bash
# Terminal 1 — API
cd server
npm install
npm start                 # http://localhost:3000

# Terminal 2 — UI
cd client
npx serve -l 5500         # http://localhost:5500
# (or use VS Code Live Server on port 5500)
