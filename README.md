# Version Control Group Exercise: Collaborative Development with Git & GitHub

## Overview

In this exercise, you will work in small groups to practice **real-world version control workflows** using **Git and GitHub**. You will collaborate on a shared codebase, create branches, make commits, open pull requests, review each other’s work, and resolve a merge conflict.

This exercise is designed to simulate how development teams work in professional software projects.

---

## Learning Objectives

By completing this exercise, you will be able to:

* Clone a GitHub repository
* Create and switch Git branches
* Make and push commits
* Collaborate using pull requests
* Review and approve code changes
* Resolve merge conflicts
* Explain why branching and pull requests are important in team development

---

## Group Requirements

* **Group size:** 3–4 students
* Each student **must**:

  * Create at least one branch
  * Make at least one commit
  * Push changes to GitHub
  * Participate in a pull request (as author or reviewer)

---

## Repository Setup

1. One group member will act as the **Maintainer**.
2. The Maintainer creates a new GitHub repository (or uses the instructor-provided template).
3. The Maintainer adds all group members as collaborators.
4. All group members clone the repository locally (skip this step if using Codespaces):

```bash
git clone <repository-url>
cd <repository-name>
```

---

## Branching Rules

* **Do not commit directly to `main`.**
* Each student must work on their **own feature branch**.
* Use the following naming convention:

```bash
git checkout -b feature/<your-name>-section
```

---

## Assigned Tasks

Each group member will be responsible for a unique change to the project. Examples include:

* Adding an **About** section
* Adding a **Team Members** section
* Adding a **Project Description** section
* Updating basic styling or adding a footer

Your instructor may assign specific tasks, or your group may divide them evenly.

---

## Making Changes and Committing

1. Make your assigned change in the codebase.
2. Stage and commit your work with a clear message:

```bash
git add .
git commit -m "Add About section"
```

3. Push your branch to GitHub:

```bash
git push origin feature/<your-name>-section
```

---

## Pull Requests & Code Review

1. Open a **Pull Request (PR)** from your branch into `main`.
2. Assign at least **one group member as a reviewer**.
3. Reviewers must:

   * Leave at least one comment
   * Approve the pull request
4. The PR can then be merged into `main`.

---

## Merge Conflict Activity

To practice conflict resolution:

* Two group members will intentionally edit the **same line** in the same file.
* One pull request will be merged first.
* The second pull request should produce a **merge conflict**.

### Resolving the Conflict

* Resolve the conflict using GitHub’s conflict editor or locally.
* After resolving, commit the fix:

```bash
git add <file>
git commit -m "Resolve merge conflict"
git push
```

---

## Deliverables

Your group must submit:

* A link to the GitHub repository
* Evidence that:

  * Each member created a branch
  * Each member made at least one commit
  * Each member participated in a pull request
  * At least one merge conflict was resolved

---

## Reflection Questions

Be prepared to discuss or submit short answers to the following:

1. Why is branching important in collaborative development?
2. What caused the merge conflict?
3. How did your group resolve it?
4. What problems might occur if everyone worked directly on `main`?

---

## Notes

* Commit early and often.
* Use clear commit messages.
* Communicate with your group before merging changes.

This exercise mirrors professional development workflows—focus on **process**, not just the final code.
