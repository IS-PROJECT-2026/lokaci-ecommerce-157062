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

<img width="1524" height="553" alt="image" src="https://github.com/user-attachments/assets/c65818e5-784d-4013-9894-50601182523b" />

- **Caption:** Three milestones namely Site Foundation, Product Catalogue, and Polish and Deploy, each fully closed with all linked issues (3/3, 2/2, 3/3) completed before merging to main.

### B. Project Board

_Provide a screenshot of your GitHub Project Board with your issues organized dynamically across columns (To Do, In Progress, Done)._

<img width="1568" height="526" alt="image" src="https://github.com/user-attachments/assets/ff2c4a46-33ec-4595-a3f2-4273a9e9ac95" />

- **Caption:** Kanban board mid-project, showing issues actively distributed across To Do, In Progress, and Done as work progressed through Milestones 1 and 2.

### C. Branching Architecture

_Provide a screenshot showing your local or remote Git branch list, highlighting your use of conventional, issue-linked naming patterns (e.g., `feat/`, `fix/`, `style/`)._

<img width="1568" height="375" alt="image" src="https://github.com/user-attachments/assets/4b588d90-2bc9-45ac-9cb8-ed9ad1f86913" />

- **Caption:** Branch list following the category/issue-number-description and category/conflict-number-letter naming conventions, e.g. feat/1-base-structure, feat/2-nav-hero, feat/4-product-catalog, and the design/conflict-1-* series used for the merge conflict demos.

### D. Pull Requests & Traceability

_Provide a screenshot of a completed or open Pull Request (PR) on GitHub that clearly shows it is linked to a related development issue._

<img width="1148" height="215" alt="image" src="https://github.com/user-attachments/assets/eb252762-fff5-4174-a796-3d13806f1bcd" />

- **Caption:** PR #10 merging feat/2-nav-hero into main, with "Closes #2" in the title directly linking it to its source issue.

---

## 5. Merge Conflict Evidence

You must engineer **three merge conflicts**, each triggered by a **different cause** from those covered in the lecture. For Conflict 1, document the full resolution lifecycle. For Conflicts 2 and 3, provide the conflict marker screenshot and identify the cause.

> **Marks:** Conflict 1 full chronology (2 marks) · Conflict 2 (1 mark) · Conflict 3 (1 mark) · All three use distinct causes (1 mark) = **5 marks total**

---

### Conflict 1 — Full Chronology

**What cause did you use?** Same Line edit

#### Step 1: Generating the Clash

_Screenshot showing the merge attempt and the conflict warning._

<img width="292" height="342" alt="image" src="https://github.com/user-attachments/assets/3e2b3b6b-486a-4534-9ca1-c04e65683dde" />


- **Caption:** Network graph showing design/conflict-1-c and design/conflict-1-d diverging from the same commit on main, then converging at the merge point — the structural setup that produced the conflict when both branches edited the same subtitle line.

#### Step 2: Inside the Code Editor (Conflict Markers)

_Screenshot showing the raw, unresolved conflict markers (`<<<<<<< HEAD`, `=======`, `>>>>>>>`) in your editor._

<img width="1545" height="301" alt="image" src="https://github.com/user-attachments/assets/840444b1-10cb-4ce5-b679-63f6d8f6d2eb" />

- **Caption:** Both <p> subtitle lines from the two diverging branches, side by side inside Git's conflict markers - Curated timepieces, just for you! from HEAD (branch D) and Handpicked watches, delivered with love. from main (branch C's merged version). Neither could be auto-selected since both modified the identical line independently.

#### Step 3: Resolution & Clean Merge

_Screenshot of your clean Git history or completed PR showing the conflict was resolved and merged._

<img width="1568" height="283" alt="image" src="https://github.com/user-attachments/assets/ba89bd32-8f09-4c43-92f8-6bcb2c3a0b63" />

- **Caption:** Merge commit 7a2289e completing PR #14, with two parent commits confirming a true merge occurred (not a fast-forward) — the conflict was resolved and the branch merged cleanly into main.

---

### Conflict 2 — Different Cause

**What cause did you use?** The Appended List

**Why does this cause trigger a conflict?** Two branches (design/conflict-2-a and design/conflict-2-b) each independently added a new link to the end of the same <footer> element. Since both insertions targeted the same position with no shared edit between them, Git couldn't determine which line should come first and flagged it as a conflict.

<img width="1568" height="210" alt="image" src="https://github.com/user-attachments/assets/a7a04252-66f9-4a32-8aa5-50170a6fe4ac" />


- **Caption:** WhatsApp link (HEAD, branch B) and Instagram link (main, branch A's merged version) both inserted at the same position inside the footer — resolved by keeping both.

---

### Conflict 3 — Different Cause

**What cause did you use?** Delete vs. Modify

**Why does this cause trigger a conflict?** [1–2 sentences explaining the mechanism]

<img width="1568" height="103" alt="image" src="https://github.com/user-attachments/assets/4b984eab-4649-47b1-a627-f145e742d22f" />


- **Caption:** Branch design/conflict-3-a deleted README.md entirely, while design/conflict-3-b, based on the same earlier commit, modified its content instead. Git can't automatically decide whether the file should exist or not, so it flags a modify/delete conflict rather than a text-level one. Resolved by keeping the modified version and discarding the deletion.

---

##

## 6. Feedback & Evaluation

To help improve this course for future engineering cohorts, please take 2 minutes to fill out the anonymous feedback form. Your honest review helps shape how this program is taught next semester!

- [ ] **Anonymous Evaluation Form:** [Course & Instructor Evaluation](https://forms.gle/YLybnsyXXErKEg3s9)

---

## Final Submission

Once your repository is complete, submit your work through the official submission form below. The form will **stop accepting responses after Monday, August 17th, 2026** — no late submissions will be accepted.

> **Submission Form:** [https://forms.gle/KrT4VxtFtkU3wtYu8](https://forms.gle/KrT4VxtFtkU3wtYu8)
