# Setup Remote For New Branches Automatically

Run `git config --global push.autoSetupRemote true` to avoid having to write `git push -u origin <new-branch-name>` every time you want to push a new branch to the remote.

This works best in a context where you only use one remote.
