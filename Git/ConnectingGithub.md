# How to Connect Git with Github

## Creating New Repository from Start

Starting from creating a new Git directory.

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

Must have Git already initialized and commited.

```
git remote add origin https://github.com/GithubUserName/Project-Name.git
git branch -M main
git push -u origin main
```
