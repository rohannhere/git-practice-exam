# Git & GitLab Practical Assignment Report

## Overview
This document explains the steps taken to successfully complete the Git and GitLab practical assignment. It covers everything from basic repository setup to advanced tasks like merge conflict resolution and repository mirroring.

---

## Task Execution Details

### Task 1: Create a GitHub Repository
  -  Created a new repository on GitHub named git-practice-task.
  -  Set the visibility to Public and initialized it with a default README file.

---

### Task 2: Clone the Repository

  - Opened the terminal and cloned the repository to the local machine using the git clone command.
  - Navigated into the project directory using the cd command to begin working.

---

### Task 3: Initial Development on Main Branch

  - Opened the README.md file and added my Name, Batch Name, and Course Name.
  - Saved the file, staged the changes, and committed them with a descriptive message.
  - Pushed the updated README to the main branch on GitHub.

---

### Task 4 & 5: Feature-A Branch and Pull Request

  - Created and switched to a new branch named feature-A.
  - Created an index.html file and added some basic HTML code.
  - Committed the file and pushed the feature-A branch to GitHub.
  - Navigated to GitHub and opened a Pull Request from feature-A to main, leaving it open without merging.

---

### Task 6: Feature-B Branch and Pull Request

  - Switched back to the main branch locally and created a second branch named feature-B
  - Opened the index.html file and modified the exact same lines that were edited in Feature-A.
  - Committed these changes and pushed feature-B to GitHub.
  - Opened a second Pull Request from feature-B to main.

---

### Task 7: Merge Feature-A

  - Went to the GitHub Pull Requests tab.
  - Reviewed the code for feature-A and successfully merged it into the main branch.

---

### Task 8 & 9: Handle Merge Conflict and Complete Merge

  - Attempted to merge the feature-B Pull Request on GitHub and was blocked due to a merge conflict.
  - To resolve this, I switched to the feature-B branch locally and pulled the latest changes from main.
  - Opened index.html, manually resolved the conflict by keeping the correct lines of code.
  - Committed the resolved file and pushed the update back to GitHub.

---

### Task 10: Fork and Contribute

  - Found a public repository on GitHub and clicked the "Fork" button to copy it to my account.
  - Cloned the forked repository to my local machine.
  - Made a small, helpful edit to the README file, committed the change, and pushed it to my fork.
  - Created a new Pull Request from my fork back to the original repository.

---

### Task 11: GitLab Repository Setup

  - Created a new private repository on GitLab.
  - Cloned it to my local machine using SSH.
  - Created the required folder and file structure (src/app.py and docs/guide.md), along with a README.md.
  - Committed the new directory structure and pushed it to GitLab.

---

### Task 12: Repository Mirroring

  - In the GitLab repository settings, navigated to the Repository section and selected Mirroring Repositories.
  - Entered the URL of the GitHub repository (git-practice-task) and provided a GitHub Personal Access Token for authentication.
  - Set the mirror direction to "Push".
  - Made a test commit on GitLab, and verified that the change automatically appeared in the GitHub repository.

---

### Task 13: Branch Protection

  - Went to the Settings of the GitHub repository and clicked on "Branches".
  - Added a branch protection rule for the main branch.
  - Checked the box to "Require a pull request before merging" and saved the rules.
  - Attempted to push a change directly to main from my local terminal and confirmed that the push was successfully blocked.

---

## Assignment Completion Status

| Task | Description | Status |
|--------|-------------|---------|
| 1 | GitHub Repository Creation | ✅ Completed |
| 2 | Repository Clone | ✅ Completed |
| 3 | Initial Development on Main Branch | ✅ Completed |
| 4 | Feature-A Branch Creation | ✅ Completed |
| 5 | Pull Request (feature-A → main) | ✅ Completed |
| 6 | Feature-B Branch Creation | ✅ Completed |
| 7 | Merge Feature-A | ✅ Completed |
| 8 | Merge Conflict Resolution | ✅ Completed |
| 9 | Merge Feature-B | ✅ Completed |
| 10 | Fork and Contribution | ✅ Completed |
| 11 | GitLab Repository Setup | ✅ Completed |
| 12 | Repository Mirroring | ✅ Completed |
| 13 | Branch Protection Configuration | ✅ Completed |
| 14 | Final Verification | ✅ Completed |


