# Team Tools Guide

A short guide comparing the tools our team uses for collaborative development.



## About the project



This repository is a teamwork exercise (TP 5, ESI-SBA). Two students use

GitHub to collaborate with branches, issues, pull requests and code review.



 ## Tools covered



 -  * *Git * *: version control system that tracks changes in files.

 -  * *GitHub * *: hosts repositories and provides collaboration tools.

 -  * *Issues * *: track tasks, bugs and ideas.

 -  * *Branches * *: let each person work without breaking `main`.

 -  * *Pull requests * *: propose changes and collect reviews before merging.



## How to use this guide:

For detailed team rules, see CONTRIBUTING.md.


1 . Clone the repository:

  ```

  git clone https://github.com/abrar07KH-eng/team-tools-guide.git

  ```

2. Start from an up-to-date main branch, then create your branch:
   ```
   git checkout main
   git pull origin main
   git checkout -b docs/your-task
   ```

3 . Make your changes, then commit and push:

  ```

 git add .

 git commit -m "Describe your change"

  git push -u origin docs/your-task

 ```

4 . Open a pull request on GitHub and mention the issue (for example `Closes #1`).

5 . Wait for a teammate to review, then merge.



Nobody commits directly to `main`.



 ## Authors



 - Student A: KOUADRI HABBAZ Abrar

 - Student B: KIRANI Khadidja

