# Git-confess
## Terminal Confessions

> *"I ran `rm -rf` on the wrong directory, and other true stories from IT survival."*

Welcome to **Terminal Confessions**—a collection of real-world post-mortems, epic infrastructure blunders, and mysterious bugs written by developers, sysadmins, and DevOps engineers who lived to tell the tale.

The goal isn't to shame anyone; it's to learn from the chaotic, hilarious, and downright bizarre situations we encounter when building and maintaining software.

---

##  Featured Confessions

| Category | Title | Takeaway |
| :--- | :--- | :--- |
| **DevOps** | [The $14,000 AWS Lambda Loop](./confessions/2026-01-aws-loop.md) | Always set cloud billing alarms on Day 1. |
| **Database** | [The Drop Table Incident of 2024](./confessions/2024-08-drop-table.md) | Test backups *before* you need them. |
| **Frontend** | [The Infinite Re-Render That Crashed Chrome](./confessions/2025-03-react-loop.md) | Dependency arrays in `useEffect` matter. |
| **Security** | [When the API Key Met Public GitHub](./confessions/2025-11-api-leak.md) | Use environment variables and secret scanners. |

---

##  Anatomy of a Good Confession

Every story here follows a simple 4-part structure:

1. **The Context:** What were you trying to build or fix?
2. **The Incident:** What went terribly wrong?
3. **The Panic:** How long did it take to figure out?
4. **The Lesson:** What check, script, or process was put in place so it never happens again?

---

##  How to Submit Your Story

Got a war story? We'd love to publish it anonymously (or credited to you).

1. **Fork** this repository.
2. Create a markdown file in `/confessions/` using our template:
   ```bash
   cp templates/confession-template.md confessions/YYYY-MM-your-story-slug.md
