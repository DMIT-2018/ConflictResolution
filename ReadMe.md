# Conflict Resolution - Draft

This repository is an example of how to deal with merge conflicts.

Here is an example of the current branch tree.

```
bug fix ->             o---o---o
                      /
dev     ->   o---o---1---o---o---o
            /     \           \
master  -> o---o---o---2---o---o---o---o
```


----

## Instructions

1. {optional} [Fork](https://github.com/login?return_to=%2FDMIT-2018%2FConflictResolution) this repository to your own account.
2. Clone the repository to your computer
3. Open a Git Shell and type the following: `git merge dev` This should create a merge conflict.
4. Type the following in the git shell to start the default merge tool (probably [kdiff3]()). `git mergetool`

In the mergetool, you will have to decide which information you want to keep in the merge. Merge conflicts are, by their nature, specific to whose code/version you plan to keep. You can also do some manual edits if one or the other version isn't what you want.

For more information, follow [this link](http://xkcd.com/1597/) and [this link](http://explainxkcd.com/wiki/index.php/1597:_Git).
Whatever you do, don't do [this](https://xkcd.com/1296/).
