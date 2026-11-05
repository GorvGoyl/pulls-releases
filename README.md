# Pulls

A Mac app for reading and merging GitHub pull requests: the description,
checks, a side-by-side diff with syntax colors, and the merge button, one
pull request per tab.

This repository only holds its builds. Each one is signed with a Developer
ID, notarized by Apple, and signed again for Pulls' updater.

## Install

1. Download **[Pulls.zip](https://github.com/GorvGoyl/pulls-releases/releases/latest/download/Pulls.zip)**
   and move **Pulls** to your Applications folder.
2. Sign in to GitHub with the GitHub CLI once: `gh auth login`. Pulls uses
   that account.
3. Open Pulls. To open pull request links in it, turn on
   *Settings ▸ Links ▸ Open GitHub pull request links in Pulls*.

Needs macOS 26 or later.

## Updates

Pulls checks for a new build every hour and installs it in the background
while none of its windows are open. While windows are open, a banner says a
new version is ready: *Restart to Update* takes one click, and your tabs come
back. *Settings ▸ Updates* shows the version and has *Check for Updates…*.
