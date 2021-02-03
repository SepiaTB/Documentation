# How to set up git in a new Project

## Creating New Repository from Start

```
echo "# Project-Name" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GithubUserName/Project-Name.git
git push -u origin main

```

## Push Locally existing Repository

```
git remote add origin https://github.com/GithubUserName/Project-Name.git
git branch -M main
git push -u origin main

```
