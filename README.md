# GIST 415 — Unit 1: Onboarding, Git Workflows & Open Source

This is your **Unit 1 repository**. You create it once, in Assignment 1, and use it for all six Unit 1 assignments. Do not create another repository for this unit.

All of your Unit 1 answers go in **one file**: [`SUBMISSION.md`](SUBMISSION.md). Screenshots go in `screenshots/`.

## Setting Up This Repository (Assignment 1)

1. On the template page, click **Use this template** → **Create a new repository**
2. Set **Owner** to the class GitHub organization (the name is in the D2L course announcement), not your personal account
3. Name it exactly `gist415-unit-1-YOUR_NETID` (for example `gist415-unit-1-jsmith`)
4. Set visibility to **Private**
5. Click **Create repository**, then clone it with GitHub Desktop (**File → Clone Repository**)
6. In GitHub Desktop, create a branch named `unit-1-work` (**Current Branch → New Branch**) and click **Publish branch**

## Assignments

| Assignment | Section in `SUBMISSION.md` | Points |
|---|---|---|
| A1: Course Setup & Software Installation | Assignment 1 | 15 |
| A2: GitHub Essentials — Your First Branch and Pull Request | Assignment 2 | 15 |
| A3: Git Concepts and the Hello World Tutorial | Assignment 3 | 20 |
| A4: GitHub Branching Workflow | Assignment 4 | 15 |
| A5: GitHub Desktop | Assignment 5, `screenshots/screenshot-desktop.png` | 15 |
| A6: Open Source Discovery | Assignment 6 | 20 |
| **Unit 1 total** | | **100** |

Full instructions for each assignment are in D2L.

## How to Submit

You work on **one branch** and open **one Pull Request** for the whole unit.

1. In Assignment 1, create a branch named `unit-1-work` from `main` and publish it; in Assignment 2, switch to it
2. Fill in each assignment's section of `SUBMISSION.md` as you complete it
3. Commit and push to `unit-1-work` after each assignment
4. In Assignment 2, open a Pull Request from `unit-1-work` → `main`, titled `Unit 1 Submission — YOUR_NETID`
5. Keep adding commits for Assignments 3–6; the same Pull Request updates automatically
6. When all six sections are complete, submit the Pull Request URL in the D2L Unit 1 submission folder

**Do not merge the Pull Request.** Leave it open for instructor review.

## Repository Contents

```
├── README.md        ← this overview
├── SUBMISSION.md    ← where you add all assignment responses
└── screenshots/     ← folder for unit images
```

## Automated Checker

When you open or update your Pull Request, a GitHub Action posts a comment that checks `SUBMISSION.md` and lists, for each assignment, whether its section is answered and its required files are present. Make sure every section shows ✅ before you submit your Pull Request URL to D2L.
