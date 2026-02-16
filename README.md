Github Commands:
whenever you want to push your code on your github, first you need to generate your token.This token will use only one time when you create your new repositorty or in simple words called folder.

Lets start our code to push our github from locally.
1-git init
2-git remote remove origin
3-git remote add origin https://[TOKEN]@github.com/[REPO-OWNER]/[REPO-NAME] (This command use only one time when create new repo.)
4-git add -A
5-git commit -m "write any message here"
6-git push origin main
