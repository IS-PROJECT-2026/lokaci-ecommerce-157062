# Project Submission Report

## 1. Student Details

- **Full Name:** Michelle Chambira
- **GitHub Username:** Chambira1
- **Email:** michelle.chambira@strathmore.edu

---

## 2. Deployed Project Link

- **Live GitHub Pages URL:**
  https://is-project-2026.github.io/lokaci-ecommerce-157062/

---

## 3. Reflection — Grounded in Your Git History

### A. My Best Commit

- **Commit URL:** https://github.com/IS-PROJECT-2026/lokaci-ecommerce-157062/commit/367321ed753e1fa5034c51a23dd82676681d1a2d

- **Why this one?** The commit's naming structure follows the good practices shown in class. The commit also went in easily without any problems, making my site have a header and a nav bar quite easily.

### B. A Mistake or Struggle

- **Link to the evidence:** https://github.com/IS-PROJECT-2026/lokaci-ecommerce-157062/commit/f2899f678735833b33750bda5fe921dc49517baf
- **What happened and how did you recover?** While engineering the first merge conflict, I created a second branch but ran `git pull` before actually committing my change on it. Since there was nothing local to conflict with, Git fast-forwarded silently instead of producing a real conflict, and I lost the demo. I recreated the branch from the exact commit before the first branch was merged, made sure to commit the edit before pulling, and got a genuine conflict the second time.

### C. A Pull Request You're Proud Of

- **PR URL:** (https://github.com/IS-PROJECT-2026/lokaci-ecommerce-157062/commit/7a2289e662b2515cdfd033108987bb080e91d9e4)
- **What did you check before merging?** I reviewed the Files changed tab to confirm the conflict markers had been fully removed, that only the intended `<h1>`/`<p>` line was affected, and that no unrelated whitespace or formatting changes had crept in from the merge.

### D. One Thing You Would Do Differently

- **What would you change?** I'd push an initial commit to `main` (even just a placeholder README) before creating any feature branches. Because I skipped this, my first branch had nothing to compare against when opening a PR, and I had to fix it retroactively with an orphan branch; a step that wouldn't have been necessary with a proper starting commit.
- **Link to the evidence of the original decision:** (https://github.com/IS-PROJECT-2026/lokaci-ecommerce-157062/commit/77f49f2a1b67c25bcc5221547e7c69ea55959f7f)

---

## 4. Screenshots of Key GitHub Features

Demonstrate your workflow mechanics by embedding your screenshots below.

> **CRITICAL FOR WORKING IMAGES:** Do not type manual folder paths. Edit this file directly on the GitHub web interface, click on the blank line below each prompt, and **paste (Ctrl+V / Cmd+V)** your screenshot. GitHub will automatically upload the file and generate a permanent, working image link for you.

### A. Milestones and Issues

_Provide a screenshot showing your active milestone(s) and the granular tracking issues linked directly to them._

[PASTE YOUR MILESTONE SCREENSHOT DIRECTLY HERE]

- **Caption:** [Write a brief sentence describing your milestones here]

### B. Project Board

_Provide a screenshot of your GitHub Project Board with your issues organized dynamically across columns (To Do, In Progress, Done)._

[PASTE YOUR PROJECT BOARD SCREENSHOT DIRECTLY HERE]

- **Caption:** [Write a brief sentence describing your board state here]

### C. Branching Architecture

_Provide a screenshot showing your local or remote Git branch list, highlighting your use of conventional, issue-linked naming patterns (e.g., `feat/`, `fix/`, `style/`)._

[PASTE YOUR BRANCHING SCREENSHOT DIRECTLY HERE]

- **Caption:** [Write a brief sentence describing your branch list here]

### D. Pull Requests & Traceability

_Provide a screenshot of a completed or open Pull Request (PR) on GitHub that clearly shows it is linked to a related development issue._

[PASTE YOUR PULL REQUEST SCREENSHOT DIRECTLY HERE]

- **Caption:** [Write a brief sentence describing your PR and what issue it closes]

---

## 5. Merge Conflict Evidence

You must engineer **three merge conflicts**, each triggered by a **different cause** from those covered in the lecture. For Conflict 1, document the full resolution lifecycle. For Conflicts 2 and 3, provide the conflict marker screenshot and identify the cause.

> **Marks:** Conflict 1 full chronology (2 marks) · Conflict 2 (1 mark) · Conflict 3 (1 mark) · All three use distinct causes (1 mark) = **5 marks total**

---

### Conflict 1 — Full Chronology

**What cause did you use?** [Name the type of conflict cause from the lecture]

#### Step 1: Generating the Clash

_Screenshot showing the merge attempt and the conflict warning._

[PASTE SCREENSHOT OF ATTEMPTED MERGE / TERMINAL WARNING HERE]

- **Caption:** [Describe which two branches collided and the warning received]

#### Step 2: Inside the Code Editor (Conflict Markers)

_Screenshot showing the raw, unresolved conflict markers (`<<<<<<< HEAD`, `=======`, `>>>>>>>`) in your editor._

[PASTE SCREENSHOT OF RAW CONFLICT MARKERS HERE]

- **Caption:** [Explain what caused the dispute and your reasoning for the final version]

#### Step 3: Resolution & Clean Merge

_Screenshot of your clean Git history or completed PR showing the conflict was resolved and merged._

[PASTE SCREENSHOT OF CLEAN RESOLUTION HERE]

- **Caption:** [Describe the final state after resolution]

---

### Conflict 2 — Different Cause

**What cause did you use?** [Name the type of conflict cause — must be different from Conflict 1]

**Why does this cause trigger a conflict?** [1–2 sentences explaining the mechanism]

[PASTE SCREENSHOT OF CONFLICT MARKERS FOR CONFLICT 2 HERE]

- **Caption:** [Brief description of the conflicting branches and file]

---

### Conflict 3 — Different Cause

**What cause did you use?** [Name the type of conflict cause — must be different from Conflicts 1 and 2]

**Why does this cause trigger a conflict?** [1–2 sentences explaining the mechanism]

[PASTE SCREENSHOT OF CONFLICT MARKERS FOR CONFLICT 3 HERE]

- **Caption:** [Brief description of the conflicting branches and file]

---

##

## 6. Feedback & Evaluation

To help improve this course for future engineering cohorts, please take 2 minutes to fill out the anonymous feedback form. Your honest review helps shape how this program is taught next semester!

- [ ] **Anonymous Evaluation Form:** [Course & Instructor Evaluation](https://forms.gle/YLybnsyXXErKEg3s9)

---

## Final Submission

Once your repository is complete, submit your work through the official submission form below. The form will **stop accepting responses after Monday, August 17th, 2026** — no late submissions will be accepted.

> **Submission Form:** [https://forms.gle/KrT4VxtFtkU3wtYu8](https://forms.gle/KrT4VxtFtkU3wtYu8)
