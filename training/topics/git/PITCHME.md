---

#### Git introduction

@ul

- Distributed version control.
  - No central server.
  - Free of charge backups.
- Powerful branching and merging.
- Adapts to ANY workflow.
- Fast, reliable and stable file format
- free & opensource

@ulend

@snap[south span-80 text-08 text-left]
by Linus Torvalds
@snapend

---

@snap[north]

#### Concepts

![](assets/img/index1@2x.png)

---

#### Terminology

@ul

- local

  - Untracked files
  - commit
  - feature branch

- remote
  - upstream
  - remote
  - clone (download)
  - fork (copy)
  - fetch vs pull
  - push

@ulend

---

#### github flow - feature branch

@div[left-40]
<br/>
![](assets/img/feature_branches.png)
@divend

@div[right-60]
<br/>
@ul

- Short live branch
- @color[red](Protect) mainstream work
- Change proposals @color[blue](ONLY!)

@ulend  
@divend

Note:

Commit often and push frequently fail fast

A simplified branching strategy
All features and fixes first go to master
Create a feature/bugfix branch to do all work
Use merge requests to merge to master

---

#### Commit message

@ul

- should reflect your intention
- commit message should explain why
- short
- start with verb
- present time
- english? vs nationalization

@ulend

Note:

quality - look at your past commits can you understand them Yourself?
look at others commits - are they understandable?

@color[blue](Quality:)
do it for others
@color[blue](invest) some time

---

#### Resources

self paced git learning

1. [katacoda](https://www.katacoda.com/courses/git)
1. [pro git book](https://git-scm.com/book/en/v2)
1. [understanding the github flow](https://guides.github.com/introduction/flow/)

---

### Workshop, Hands-on

Note:

TODO parusoti uzduotis

---

#### Configure Git

TODO perkelti i gitlab presentacija?

```bash
git config --global user.name "Your Name"
git config --global user.email you@example.com
```

---

#### Create/Initialize project

```bash
mkdir ~/git_projects
cd ~/git_projects
git init
```

@snap[south text-06 span-100]

@[1-2](create directory)
@[3](initialize git repository)

@snapend

Note:

TODO perdaryti ir per explorer
ads winexplorer picture :)

---

#### Committing

```bash
# Edit `some_file`
git status
git diff
git add <file>
git commit -m 'Short & clear commit message'
git push origin master
git log
```

@snap[south text-06 span-100]

@[1](Edit file)
@[2-3](See changed files, view the differences)
@[4](Stage the file)
@[5](Commit)
@[6](Push the commit to the remote)
@[7](View the Git log)

@snapend

---

#### Feature branching

```bash
git checkout -b meaningful_name
# Edit `some_file`
git status
git add some_file
git commit -m 'minor: lint'
git push origin meaningful_name

@snap[south text-06 span-100]

@[1](Create a new feature branch called "meaningful_name")
@[2-4](Edit file, See changed files, Stage the file)
@[5-6](Commit, push)

@snapend

---

## @color[blue](Q) / @color[green](A) ?

---

#### References

1. <https://docs.gitlab.com/ee/university/training/user_training.html>
1. <https://docs.gitlab.com/ee/university/training/gitlab_flow.html>
1. <https://www.katacoda.com>
1. <https://git-scm.com/book/en/v2>
1. <https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html>
1. <https://docs.gitlab.com/ee/topics/gitlab_flow.html#commit-often-and-push-frequently>

---

TODO

git commit burbulai visualizuoti
git merge visualizavimas - <https://www.youtube.com/watch?v=03wb9FvO4Ak&index=5&list=PLFGfElNsQthbQu_IWlNOxul0TbS_2JH-e> - 31:43 tikrinti visa faila panasu visas workflow easy paaiskintas, det i self training
```
