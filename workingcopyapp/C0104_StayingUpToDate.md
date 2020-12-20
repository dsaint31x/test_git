# 1.4 Staying up-to-date

Commits can be pushed to the remote from many sources. Other people contribute their work, or you could be doing something on a regular computer or another iOS device with results in commits that end up on the remote.

You get commits back into Working Copy through a two-step process where you `Fetch` and `Merge`. `Fetch` reads commits from the server and require a network connection. The commits will not be integrated with the local data on your device unit you `Merge`, which will combine the new commits from the server with your local data.

You can pull the list of repositories down to `Fetch` for all your repositories. If any of your repositories received new commits you will be able to `Merge` all these repositories with a single tap.

Sometimes data cannot be automatically combined because your local changes conflict with the changes from the commits fetched. These conflicts can be resolved by manually editing files and picking the wanted parts from the conflict markers tapping `the Resolve button`. A faster solution is to use the `Resolve` tool that lets you resolve conflicts for many files at once.

Performing a `Fetch` followed by a `Merge` is called `Pull`. On the remote detail screen you can `Fetch`, then `Merge` and finally `Push` with the `Sync` button.

You can configure repositories to `Rebase` instead of `Merge` commits from the Configuration page inside Repository status. This is pro configuration available to users that purchased or upgrade their ***pro unlock*** on October 17, 2018 or later.