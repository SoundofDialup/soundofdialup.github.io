---
title: Deploy an Astro site to GitHub Pages with workflows
author: Sound of Dialup
pubDatetime: 2023-08-11T18:10:34.188Z
postSlug: deploy-astro-site-to-github-pages-with-workflows
featured: false
draft: false
tags:
  - astro
  - github
  - github pages
description: How to deploy an Astro site to GitHub Pages with workflows and GitHub Actions.
---

Today I taught myself how to deploy an Astro project to GitHub Pages. There was much hair pulling, but we got there in the end!

## Table of contents

## Instructions

1. Create the repo as per a usual [GitHub Pages](/posts/github-pages) project.

2. Go into the repo `Settings > Pages` and select `GitHub Actions (Beta)` from the 'Build and deployment' source dropdown (instead of deploying from a branch).

   ![Screenshot of the build and deployment source dropdown, showing GitHub Actions selected](/assets/deploy-astro-site-to-github-with-workflows.jpg "Selecting GitHub Actions")

3. Browse available workflows and search for `Astro`.

4. Select the sample Astro workflow.

5. Ensure that _Actions Permissions_ allows for all actions and reusable workflows (`Settings > Actions > General`)

   ![Screenshot of the GitHub Actions Permissions options, with "Allow all actions and reusable workflows" selected](/assets/github-actions-permissions.jpg "Actions Permissions settings")

## What's all this then?

"**[Astro](https://astro.build/)** is the all-in-one web framework designed for speed. Pull your content from anywhere and deploy everywhere, all powered by your favorite UI components and libraries." (_Astro_, 2023)

"**[GitHub Actions](https://docs.github.com/en/actions)** allow you to automate, customize, and execute your software development workflows right in your repository. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow." (_GitHub Docs_, 2023)

"**[GitHub Pages](https://docs.github.com/en/pages/quickstart)** are public webpages hosted and published through GitHub." (_GitHub Docs_, 2023)

"**[GitHub](https://docs.github.com/en/get-started/quickstart/hello-world)** is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere." (_GitHub Docs_, 2023)
