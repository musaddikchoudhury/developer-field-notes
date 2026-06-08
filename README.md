## Developer Field Notes



## Description

A personal reference site created during ttp to collect essential Git commands, workflow habits, and daily development reminders. This project demonstrates foundational Git version control and deployment using GitHub Pages.



## Live Site

[deployed site]



## Features

Terminology Breakdown: Clear distinction between Git and GitHub.

Daily Workflow: Step-by-step guide to the edit, stage, commit, and push cycle.

Command Reference: A quick-reference list of core Git commands and their uses.

Security Reminders: Important notes on keeping sensitive files (like `.env` and `node\_modules`) out of commits.


## What I Learned

During this assignment, I learned that a file is not automatically added to a commit just because it is saved in my editor; it must be explicitly staged first using `git add`. I also learned how to use `.gitignore` right from the start to prevent sensitive files from being tracked.


## Git Practice Evidence

```text
C:\Users\musad\developer-field-notes>git log --oneline
bf96595 (HEAD -> main, origin/main) Merge pull request #6 from musaddikchoudhury/feature/responsive-styling
d9b0022 (origin/feature/responsive-styling, feature/responsive-styling) Add responsive layout and typography styling
db2b7e6 Merge pull request #5 from musaddikchoudhury/feature/safety-section
b2ba840 (origin/feature/safety-section, feature/safety-section) Update safety section text to fix PR
25d4504 Merge pull request #4 from musaddikchoudhury/feature/command-reference
d020dd1 (origin/feature/command-reference, feature/command-reference) Add command reference section
51281bd Update README.md
57783b8 Add initial CSS file
c757c3f Add initial HTML and README
8bda20e Add .gitignore file

C:\Users\musad\developer-field-notes>git log --oneline --graph --all
* bf96595 (HEAD -> main, origin/main) Merge pull request #6 from musaddikchoudhury/feature/responsive-styling
|\
| * d9b0022 (origin/feature/responsive-styling, feature/responsive-styling) Add responsive layout and typography styling
|/
* db2b7e6 Merge pull request #5 from musaddikchoudhury/feature/safety-section
|\
| * b2ba840 (origin/feature/safety-section, feature/safety-section) Update safety section text to fix PR
|/
* 25d4504 Merge pull request #4 from musaddikchoudhury/feature/command-reference
|\
| * d020dd1 (origin/feature/command-reference, feature/command-reference) Add command reference section
|/
* 51281bd Update README.md
* 57783b8 Add initial CSS file
* c757c3f Add initial HTML and README
* 8bda20e Add .gitignore file

C:\Users\musad\developer-field-notes>git branch --all
  feature/command-reference
  feature/responsive-styling
  feature/safety-section
* main
  remotes/origin/feature/command-reference
  remotes/origin/feature/responsive-styling
  remotes/origin/feature/safety-section
  remotes/origin/main
