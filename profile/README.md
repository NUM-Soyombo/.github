### GIT INSTRUCTION - ДАГАХТУН, САХИХТУН!!!
1. Create new branch from develop:
```
$ git checkout develop
$ git pull origin develop
$ git checkout -b [LABEL-TYPE]/[ISSUE-NUMBER]_[ISSUE-TITLE]
```
2. Then, make empty commit for creating Pull Request (PR):
```
$ git commit --allow-empty -m 'Empty commit for creating [WIP] Pull Request'
$ git push -u origin HEAD
```

Whenever you finish the work of the day, please commit and push. Then, other members can check your code.
```
$ git add .
$ git commit -m '[ISSUE-NUMBER] [COMMIT-MESSAGE]'
```
Before you push your commit(s), please verify there is no new changes at develop branch:
```
$ git pull origin develop
```
Congratulations, now you can push your code:
```
$ git push
```


> The golden rule of git rebase is to never use it on public branches.
