## Clone a branch

git checkout -b feature/BLABLA main

## Check differences between branches

git diff feature/BLABLA main

## How to rebase

git add .
git commit -m "message"
git push origin feature/BLABLA

git checkout main
git fetch
git pull
git switch -
git rebase main

## resolve issues if exist and then

git push --force-with-lease

## NPM

## Update all dependencies in a Json (might have an issue in Windows if script execution are disabled)

## If happens then Ausfürhren-> gpedit.msc Administrative Vorlagen->Windows Komponenten->Windows Powershell-->Scriptführung -> activieren -> Click Acitvieren und unten Alle Scripts ## zulassen

npm i -g npm-check-updates
ncu -u
npm install
