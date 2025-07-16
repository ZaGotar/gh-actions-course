# GitHub Actions: The Complete Guide from Beginner to Expert
Resources:
  https://github.com/lm-academy/github-actions-course
  https://github.com/lm-academy/github-actions-course-example-e2e


Updates regarding the repository and package versions used in the course
  Hello once again! I make sure to keep the code constantly updated to use more recent versions of third-party actions, as well as NPM packages, as they become available. I will also put up announcements in case any changes are not compatible with the course recordings, and what you need to change in order for everything to work smoothly.
  Additionally, I have renamed the repository from gh-actions-course to github-actions-course during the recordings of the course, and this has no impact whatsoever on the course (it's just an information since you will see the older version in earlier recordings). All the links to the repository are up to date, and you should be able to follow the entire content without any issues!


echo "# gh-actions-course" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:ZaGotar/gh-actions-course.git
git push -u origin main

git remote add origin git@github.com:ZaGotar/gh-actions-course.git
git branch -M main
git push -u origin main

---
Editing the Git Configuration File

There are several ways to edit the Git configuration file:

    Command-line interface (CLI): You can use the git config command to view, set, and modify the configuration file. Here are some common examples:
        View the current configuration: git config --list
        Set a global user name: git config --global user.name "John Doe"
        Set a global user email: git config --global user.email "johndoe@example.com"
        Set a repository-specific setting: git config --local user.name "John Doe"
