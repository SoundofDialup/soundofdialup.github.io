---
title: Remove user@computer from Git Bash prompt
author: Sound of Dialup
pubDatetime: 2023-08-11T01:21:15.188Z
postSlug: change-git-bash-name-in-prompt
featured: false
draft: false
tags:
  - git
description: How to change the current user and computer name displayed in Git Bash for Windows.
---

Instead of showing the current user and computer name in the git bash prompt, we can change it to whatever we like.

Git Bash prompt before:
![Screenshot of Git Bash before the change](/assets/gitbash-username-before.jpg "Default Git Bash settings")

Git Bash prompt after:

![Screenshot of Git Bash after the change](/assets/gitbash-username-after.jpg "Modified Git Bash settings")

## Table of contents

## Instructions

1. Open **C:\Program Files\Git\etc\profile.d\git-prompt.sh** (or wherever you installed Git) in your favourite text editor (e.g. [Notepad++](https://notepad-plus-plus.org/))
2. On line **15**, replace the entire line with: `PS1="$PS1"'Git '` (or even just 👉 `PS1="$PS1"''` if you don't want any text at all)
3. Save the file and restart Git Bash.

## What's all this then?

"**[Git for Windows](https://gitforwindows.org/)** focuses on offering a lightweight, native set of tools that bring the full feature set of the Git SCM to Windows while providing appropriate user interfaces for experienced Git users and novices alike." (_git for windows_, 2023)

"**[Git](https://git-scm.com/)** is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency." (_git_, 2023)
