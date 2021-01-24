# 2 Branches

**A great advantage of Git** compared to other version-control software is the ease at which **you can branch your repository** to work independently on different things. Once you are confident with the work undertaken in a branch, you can **merge** it back to one of your main branches.

In Working Copy you can do this from the Repository screen by tapping the current branch name to access a list of branches. **Tapping a branch** brings up a detail view where you can 
* checkout the branch (make it current), 
* rename or 
* delete it.

You can *swipe left* on branches to **`Checkout`, `Rename` or `Delete`** without having to go to the detail screen and when a local branch is ahead of its remote, you can `Push` as well.

You **create new branches** from the current one with the upper-rightmost button. To put commits on a branch you can either **`Merge` or `Rebase`**. Atlassian has a great [tutorial](https://www.atlassian.com/git/tutorials/merging-vs-rebasing/) describing the differences. In both situations you change your current branch to include commits from some other branch.

`Merge` will create a merge-commit as needed, while `rebase` will rewrite commits from your current branch on top of the commits from the other branch. Working Copy will not `rebase` if this requires rewriting commits that have already been pushed to a server. You can override this behaviour by configuring the branch for History Rewriting, but this in turn requires you to `Force Push`. This also lets you [`Undo`](https://workingcopy.app/manual/commit-undo) commits already pushed to a remote.

You `Reset` the head of the current branch from the detail screen of the commit you want to become `HEAD`. This is a soft reset that leaves the working directory as before the reset which can be fixed with `Revert` as needed. If you navigate the commit list through a non-current local branch you are able to `Reset` the head of this branch. In all cases you will be told what is about to happen as you confirm the `Reset`.
