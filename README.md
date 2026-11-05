# Pulls

A Mac app for reading and merging GitHub pull requests: the description,
checks, a side-by-side diff with syntax colors, and the merge button, one
pull request per tab.

This repository only holds its builds. Each one is signed with a Developer
ID, notarized by Apple, and signed again for Pulls' updater.

## Install

1. Download **[Pulls.zip](https://github.com/GorvGoyl/pulls-releases/releases/latest/download/Pulls.zip)**
   and open **Pulls** (macOS asks once whether to open an app from the internet).
2. Pulls offers to move itself to Applications, then walks you through the
   rest: connecting GitHub (it installs the GitHub CLI for you if it's
   missing, and you approve the sign-in in your browser), opening pull
   request links in Pulls, and opening at login.

Pulls has no Dock icon: it waits in the background for pull request links.
To open it yourself, use Spotlight (⌘Space, then type "Pulls").

Needs macOS 26 or later.

## Updates

Pulls checks for a new build every hour and installs it in the background
while none of its windows are open. While windows are open, a banner says a
new version is ready: *Restart to Update* takes one click, and your tabs come
back. *Settings ▸ Updates* shows the version and has *Check for Updates…*.
