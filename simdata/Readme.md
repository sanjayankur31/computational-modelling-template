# Simulation data

Simulation data goes here.

Large files are often not allowed on normal code hosting platforms such as GitHub.
This folder can instead be managed by [git-annex](https://git-annex.branchable.com/).
Files managed by `git-annex` can then stored on a number of [storage remotes](https://git-annex.branchable.com/special_remotes/).

To make this folder managed by `git-annex`, install `git-annex` and run:

    git annex init
    git annex config --set annex.largefiles 'include=simdata/'

More information on configuring "largefiles" can be found [here](https://git-annex.branchable.com/tips/largefiles/).

You can then use `git add` normally, and any files in this folder will be managed by `git-annex` and stored on the special remote separately from your code.
