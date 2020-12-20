# 1. Commit History

The value of well-drafted commit messages becomes apparent when looking at a log of previous commits. You may do this for either the entire repository, a directory with all its files or for single files. If your commit messages are meaningful, even if you return to a project after months or years you have a much better chance of making sense of the source-code. Tap a commit to see specific changes this commit made to the files in question.

The images shown in commit-logs are determined from the email-address of the person making the commit with the help of [gravatar.com](http://gravatar.com/). At the commit-list for the entire repository you can `Checkout` old versions of your files by swiping left on a commit. Your repository will be in a ***“detached head”*** state where **you cannot commit any changes**, but if you make modifications and wish to keep these, you should create a new branch.

*Checking out **the topmost commit*** will reattach the `head` in such a way that your repository is back to normal.

When not yet pushed to a remote, **you can `Undo` your latest commit by swiping left in the commit-list**. All changes for that commit are kept in your working directory as **modified files**. If you commit again the last commit message is remembered, making it very easy to commit again to fix typos in the commit message or only commit some of the files, splitting a large commit into smaller ones. When the last commit has been undone, you can `Undo` another, letting you squash several commits into one.