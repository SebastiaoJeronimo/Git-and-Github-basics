# Git-and-Github-basics

This repository is going to be used for instructive purposes to learn the basics of git and github!

## Resources
* **Related Video:** [Git and Github basics](https://www.youtube.com/watch?v=hNsYIiLE4yI&t=10s)
* **Presentation Slides:** 
    * [Presentation Slides PDF](presentation/Git%20and%20github%20introduction.pdf) 
    * [Presentation Slides PowerPoint](presentation/Git%20and%20github%20introduction.pptx)

---

## What are Git and GitHub?
* **Git:** A version controller that tracks all changes in your code, allowing you to go back to previous versions if you make a mistake.
* **GitHub:** A website that stores your code and changes in the cloud, enabling collaboration with multiple people at the same time.
* **Repository:** A digital space to store code; it is better than working locally because it allows for easy backups and teamwork.

---

## Setup
1. **Install Git:** Download it for free at [git-scm.com/install](https://git-scm.com/install/).
2. **Verify Installation:** Run `git --version` in your terminal to confirm it is ready.
3. **GitHub Account:** Create a free account at [github.com](https://github.com/).

---

## Basic Git Commands

| Command | Description |
| :--- | :--- |
| **`git clone <url>`** | [cite_start]Copies a project from a GitHub repository to your computer[cite: 79, 80]. |
| **`git add <file>`** | [cite_start]Chooses specific changes you want to prepare for an update[cite: 81, 99]. |
| **`git commit -m "note"`** | [cite_start]Confirms your changes with a descriptive note[cite: 82, 83]. |
| **`git push`** | [cite_start]Sends your updated local changes to the GitHub repository[cite: 84, 85]. |
| **`git pull`** | [cite_start]Downloads the latest version of the code if you are missing updates[cite: 87, 88]. |
| **`git status`** | Used to check which files are modified or untracked locally. |

---

## Resolving Conflicts
When multiple people edit the same files, merge conflicts may occur. To resolve them:
1. Pull the latest changes: `git pull`.
2. Open the files to fix the conflicts manually.
3. Add and commit the resolved files.
4. Re-push your changes: `git push`.

---

*Created by Sebastião Jerónimo* 

