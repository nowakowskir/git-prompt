# git-prompt

## Description

This small script lets you get new system prompt telling on which branch you are already in.

It also lets you to see the repository name you are in. It may be useful if working with nested submodules, where changing directory from one to another changes the repository you are working on.

```
user@host:~/project/$ repo [develop]$ cd submodule/
user@host:~/project/submodule/ another-repo [master]$
```

## Installation

```[ -f $(pwd)/git-prompt.sh ] && tail -n +3 $(pwd)/git-prompt.sh >> ~/.bashrc && source ~/.bashrc```




