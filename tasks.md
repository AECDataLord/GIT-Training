# Tasks

## Create your own pet project on [GitHub](https://github.com)

```shell
mkdir -p my-pet-project
cd my-pet-project
git init
git remote add origin git@github.com:<your-gh-account>/my-pet-project.git
echo "# My pet project" > readme.md
git status
git add readme.md
git status
git commit --message "init"
git log --all --graph --oneline --decorate
git push --set-upstream origin main
git log --all --graph --oneline --decorate
```

## Calculator

Create a calculator python application that reads 2 numbers from the standard input, and writes those sum to the standard output.
