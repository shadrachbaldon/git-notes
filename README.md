# Git Notes

Personal git commands cheat sheet


### Pull changes
`git pull`


### Change latest commit message

`git commit --amend -m “<commit message>“`

`git push -f`


### Delete local commits on branch removing changes

`git reset --hard origin/<branch name>`


### Delete previous local commit on branch and retain changes

`git reset --soft origin/<branch name>`


### Show local commits

`git log --branches --not --remotes`


### Delete Local branch

`git branch -d <branch name>`


### Before push

`git fetch origin <dev>:<dev>`

`git rebase dev`

`git push -f`

