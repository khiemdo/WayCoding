# WAY CODING

## INTRODUCTION

Introduce Way about git, vscode

## TODOLIST

- [ ] learn about markdown
  - [ ] use mardown to summary school fee for 4 years. create a new file SchoolFee.md
- [ ] Learn about git
- [ ] learn about vscode

## STEP 1

- Download tools
  - [gitGUI](https://git-scm.com/downloads)
  - [vscode](https://code.visualstudio.com/download)

## LEARN ABOUT MARKDOWN

use mardown to summary school fee for 4 years. create a new file SchoolFee.md

```bash
cd $PROJECT_DIR

git config --global user.name "Mona Lisa"
git config --global user.email email@example.com
# create new branch
git checkout -b waydev
git checkout -b dkdev
# sync new content from server
git pull origin dkdev
# change branch
git checkout waydev
# merge the change
git merge dkdev

# stage your own changes
git add -A
# commit changes
git commit -m "new changes"
# upload change to server
git push origin waydev
```

### Reference

- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- https://guides.github.com/features/mastering-markdown/