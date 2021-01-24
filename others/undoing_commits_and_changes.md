# Undoing Commits & Changes

```bash
git checkout
git clean
git revert
git reset
git rm
```

In this section, we will discuss the available `undo` Git strategies and commands. It is first important to note that Git does not have a trditional `undo` system like those found in a word processing application. It will be beneficial to refrain from mapping Git operations to any traditinoal `undo` mental model. Additionaly, Git has its own nomenclature for `undo` operations that it is best to leverage in a discussion. This nomenclature includes terms like `reset`, `revert`, `checkout`, `clean` and more.

A fun metaphor is to think of Git as a timeline management utility. Commits are snapshots of a point in time or points of interest along the timeline of a projects' history. Additionally, multiple timelines can be managed through the use of branches. When `undoing` in Git, you are usually moving back in time, or to another timeline when mistakes didn't happen.

This tutorial provides all of the necessary skills to work with previously revisions of a software project. First, it shows you how to explore old commits, then it explaines the difference between reverting public commits in the project thistory vs. resetting unpublished changes on your local machine.


