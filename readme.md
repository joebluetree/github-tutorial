
# Git Hub Tutorial

## Git Hub Site
#### https://github.com
## Download Git
#### https://git-scm.com/downloads



## Setup a git account in local computer

<p>
Kindly create a git hub account and a git repository. Below is a sample a/c and repository
</p>

```
Git A/c          : ghaccount
Git Repository   : git@github.com:ghaccount/github.git
```

## Setting git in Local computer
<p>
Download and install git from site https://git-scm.com/downloads
</P



## Set default name and email
<p>
use below commands to set defauly user name and email id, which can be set globally or to a local folder only
</P

```
git config user.name "YOUR_USER_NAME"
git config user.email "YOUR_EMAIL"

git config --global user.name "YOUR_USER_NAME"
git config --global user.email "YOUR_EMAIL"
```

## Git Branching and merging
<p>
Branching is used to create a working folder (branch) where you can do changes and later when completed it can be merged to the original master branch. Below is a set of commands to create a branch namely hotfix then it is merged to master branch
</p>

```
// Create a branch hotfix
git branch   hotfix
// move to gotfix branch
git checkout hotfix
// move back to master branch
git checkout master
// merge hotfix branch to master branch
git merge    hotfix
// remove hotfix branch
git branch -d hotfix
```
