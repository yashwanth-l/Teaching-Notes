# Git

## What is it?

- It a storage medium for your source-code; also known as source control; SCM
  - GitHub
  - GitLab
  - Bitbucket
and so on..

- Interaction is via UI or via CLI(git)

- Many things to store == Organize
  - Org/Namespace
    - Repositories: Place to store; Can be public and Private
      - Branches: One "main" branch, call it main or master or anything
      - Commits: A meaningful reference to an addition/change/delete/update(- or +); it is a Random Hash
      - Tags: Reference point to a specific commit

- Remote vs Local

- From "Remote" To "Local" == clone(git clone)

- To get to Local(from Remote), we call it "clone" and use either of 2:
  - HTTPS: PAT(Personal Access Token)/Uname+Pwd
  - SSH: SSH-Keys

- Changes:
  - Add == git add filename OR git add -A OR git add . == staging for commit
  - Commit == git commit -m
  - Push == git push origin <branch-name>

- Tags:
  - git tag <tagName> <commitId>
  - git push --tags

- Branches:
  - You create a branch(**from a branch**) to which you want to make changes(Potluck Party - getting dishes)
  - Once you make changes in _your_ branch, you will create a **Change/Pull/Merge Request** to push(not git push) your changes to the main branch == Code Review
  - git branch <branchName>(creates a branch)
  - git push origin <branchName>(pushes created branch to remote)

- Checkout:
  - For moving between branches
  - git checkout <branchName>(only to move)
  - git checkout -b <branchName>(creates and moves to that branch)
