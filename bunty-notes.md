# Bunty's Class Notes on Wine-Musician
## 12/10/15

### Summary
Explain or define the terms below exercising markdown.
- remote
- forking
- pull request
- commands:
  * clone
  * push
  * add
  * status
  * merge
  * fetch
  
-------------
#### Remote
```git remote```

A remote is a repository that sits on another server, like GitHub, which I can push any data to that the repo doesn't have or fetch any differences from other repo's.

#### Forking
A fork is a copy of a repository that you manage. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

1. Go to username/reponame of the repo to fork
2. Select "Fork" button at top right to fork to your Git account
3. Copy your newly forked repo's URL with the clipboard icon
4. Clone the fork locally with `git clone https://github.com/bsomroy/wine-musician`

#### Pull Request
After making a commit to your repo, creating a **pull request** asks the user who manages the repo you cloned if they would like to accept the changes.

#### Clone
`git clone [repo URL]` clones the repo to your local server

#### Push
Use `git push` to push your local branch to a remote repository. The git push command takes two arguments:

A remote name, for example, `origin`

A branch name, for example, `master`

```git push  <REMOTENAME> <BRANCHNAME>```

As an example, you usually run `git push origin master` to push your local changes to your online repository.

#### Add


#### Status

#### Merge

#### Fetch
