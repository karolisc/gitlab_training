#### Git agenda

- introduction
- terminology
- gitlab flow
- resources
- hands on
- Q/A

---

#### Git introduction

- Distributed version control.
  - Does not rely on connection to a central server.
  - Free of charge backups.
- Powerful branching and merging.
- Adapts to ANY workflow.
- Fast, reliable and stable file format
- free & opensource
  by Linus Torvalds

---

#### Terminology, Git Concepts

- working directory
- staging area
- repository
- Untracked files
- commit
- remote
- upstream
- feature branching
- clone - download
- fork - copy
- fetch vs pull
- push
  features
- ammend commits
- undo changes

![](assets/img/index1@2x.png)

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

- should reflect your intention
- commit message should explain why
- short
- start with verb
- present time
- english? vs nationalization

Note:

commit message - present time
quality - look at your past commits can you understand them Yourself?
look at others commits - are they understandable?

Branch name - e.g. issue ref
Commit message name
@color[blue](Quality:)
do it for others
@color[blue](invest) some time

---

#### Resources

self paced git learning
[katacoda](https://www.katacoda.com/courses/git)
[pro git book](https://git-scm.com/book/en/v2)
[understanding the github flow](https://guides.github.com/introduction/flow/)

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

Create/Initialize project

TODO perdaryti ir per explorer
ads winexplorer picture :)

```bash
mkdir ~/git_projects
cd ~/git_projects
git init
```

Commands (committing)

```bash
# Edit `some_file`                               # Edit file
git status                                       # See changed files
git diff                                         # View the differences
git add <file>                                   # Stage the file
git commit -m 'Short & clear commit message'     # Commit
git push origin master                           # Push the commit to the remote
git log                                          # View the Git log
```

---

#### Feature branching

```bash
git checkout -b meaningful_name                 # Create a new feature branch called "meaningful_name"
# Edit `some_file`                              # Edit file
git status                                      # See changed files
git add some_file                               # Stage the file
git commit -m 'minor: lint'                     # Commit.
git push origin meaningful_name                 # Push.
```

---

## @color[blue](Q) / @color[green](A) ?

---

references
<https://docs.gitlab.com/ee/university/training/user_training.html>
<https://docs.gitlab.com/ee/university/training/gitlab_flow.html>
<https://www.katacoda.com>
<https://git-scm.com/book/en/v2>
<https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html>
<https://docs.gitlab.com/ee/topics/gitlab_flow.html#commit-often-and-push-frequently>

---

TODO

git commit burbulai visualizuoti
git merge visualizavimas - <https://www.youtube.com/watch?v=03wb9FvO4Ak&index=5&list=PLFGfElNsQthbQu_IWlNOxul0TbS_2JH-e> - 31:43 tikrinti visa faila panasu visas workflow easy paaiskintas, det i self training
