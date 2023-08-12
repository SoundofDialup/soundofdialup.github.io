---
title: GitHub Pages
author: Sound of Dialup
pubDatetime: 2023-08-12T03:39:34.188Z
postSlug: github-pages
featured: false
draft: false
tags:
  - github
  - github pages
  - web hosting
description: Host your own website for free on GitHub.
---

Host your own website for free on GitHub.

## Table of contents

## Instructions

1. Create a new repo named _USERNAME_.github.io (_username_ must match your GitHub username exactly)

   ![Creating a new GitHub repo](/assets/github-pages-create-repo.webp "Creating a new GitHub repo")

2. Initialise the repo with a **README**.

3. From the terminal (Git Bash or VSCode), clone your newly created repo (replace _username_, as before x2):

   ```bash
   git clone https://github.com/USERNAME/USERNAME.github.io
   ```

4. cd into the project folder and create **index.html**
5. Add, commit, and push changes:

   ```bash
   git add --all
   git commit -m "Initial commit"
   git push -u origin main
   ```

6. You're good to go! ➡ `https://USERNAME.github.io`

## What's all this then?

"**[GitHub Pages](https://docs.github.com/en/pages/quickstart)** are public webpages hosted and published through GitHub." (_GitHub Docs_, 2023)

"**[GitHub](https://docs.github.com/en/get-started/quickstart/hello-world)** is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere." (_GitHub Docs_, 2023)
