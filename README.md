# Burp Suite Mastery

A complete, offline, four-stage self-study course taking you from web security fundamentals to Burp Suite Certified Practitioner (BSCP) exam readiness.

No build step, no dependencies, no internet required to read it — just open the HTML files in a browser.

## Start here

Open **[`burp-course-hub.html`](burp-course-hub.html)** first. It links to all four stages, plus a course overview, progress tracker, and recommended lab environments.

## The four stages

| Stage | File | Weeks | Covers |
|---|---|---|---|
| 1 — Beginner | [`burp-course-beginner.html`](burp-course-beginner.html) | 1–4 | HTTP/HTTPS, cookies & sessions, authN vs authZ, OWASP Top 10, testing ethics/methodology, Burp install (Windows/macOS/Linux), CA cert setup, Proxy, Repeater, Intruder, Decoder, Comparer |
| 2 — Intermediate | [`burp-course-intermediate.html`](burp-course-intermediate.html) | 5–10 | Scanner, Sequencer, Target/scope, key extensions, SQL injection, XSS, CSRF, IDOR/BOLA, authentication & session weaknesses, access control, security misconfiguration, CORS, rate limiting |
| 3 — Advanced | [`burp-course-advanced.html`](burp-course-advanced.html) | 11–16 | SSRF, file upload, path traversal, command injection, JWT attacks, API/GraphQL security, business logic & race conditions, request smuggling, OAuth, WAF evasion, deserialization/SSTI, professional pentest methodology, CVSS scoring, sample findings |
| 4 — Assessment Prep | [`burp-course-assessment.html`](burp-course-assessment.html) | 17–20 | BSCP exam blueprint, objective-to-module mapping, two real-lab mock exams, 25 timed drills, revision checklist, consolidated flashcards, full interview question bank (18 questions with model answers &amp; examples), readiness self-assessment, exam-day strategy |

## Features

- **Fully offline** — every page is a standalone HTML document; all cross-links between stages are relative file links.
- **Enterprise-documentation design system** — a warm-neutral light/dark palette, consistent spacing and type scale, SF Pro + JetBrains Mono typography, and a minimal thin-outline icon set used throughout (no emoji, no stock imagery).
- **Dark/light theme** — toggle button in the header, or press **Ctrl+J**. Preference is remembered per page.
- **Sidebar with scrollspy** — each stage page has an "On this page" nav that highlights your current section as you scroll, on top of the top-level stage switcher.
- **Accessible by default** — skip-to-content link, visible focus rings, `prefers-reduced-motion` support, and scroll-margin so anchor links clear the sticky header.
- **Real practice links, not fiction** — labs, mock exams, and the certification track all point to actual PortSwigger pages: [Web Security Academy](https://portswigger.net/web-security), [All Labs](https://portswigger.net/web-security/all-labs), [Learning Paths](https://portswigger.net/web-security/learning-paths), and the official [BSCP certification](https://portswigger.net/web-security/certification) pages. Stage 4's two mock exams send you to pick real unsolved labs from named Academy categories rather than a made-up scenario.
- **Practical throughout** — real HTTP request/response examples, payload tables, worked Burp workflows, three full sample vulnerability findings (with CWE/OWASP mapping, reproduction steps, evidence, business impact, and remediation), knowledge checks, flashcards, and interview questions with full model answers and examples in every module.

## Scope of practice

Everything in this course is built for **authorized** targets only: your own local labs, PortSwigger Web Security Academy, deliberately vulnerable apps you run yourself (OWASP Juice Shop, DVWA, WebGoat), or engagements you hold written authorization for. Testing systems you don't own or lack permission to test is illegal under the CFAA (US) and equivalent computer-misuse laws elsewhere.

## Recommended lab environments

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) — free, purpose-built labs for every topic in this course
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) — modern vulnerable app for open-ended practice
- DVWA (Damn Vulnerable Web Application) — classic, adjustable-difficulty practice target
- WebGoat — OWASP's guided lesson-style vulnerable app
