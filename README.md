



# Gerrit Usage



## What is _Gerrit_


## How to use Gerrit


### Add SSH Key


+ Generate SSH key on your local machine 
    -   `ssh-keygen -t rsa`

+ Add SSH to Gerrit account

add figure

### Find the project you want to contribute

`Browse` -> `Repositories`

You can type the project name to find it. For example, type `NominisYS` to find `NominisYS/gerrit_demo`.


### Fork the project

Go to project page and copy `git clone ......`.


## Contribute code and commit


```bash
git add -A
git commit -a -m "add comment"
```

## Push to gerrit server

```bash
git push origin HEAD:refs/for/master
```

`refs/for/<target-branch>` 








