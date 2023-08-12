---
title: Use a Custom URL on GitHub Pages
author: Sound of Dialup
pubDatetime: 2023-08-08T10:03:34.188Z
postSlug: github-pages-custom-url
featured: false
draft: false
tags:
  - github
  - github pages
  - web hosting
description: Change username.github.io to www.example.com and example.com.
---

Change _username_.github.io to www.example.com and example.com.

## Table of contents

## Instructions

### On your DNS provider (e.g. Namecheap)

1. Create a `CNAME` record pointing www (www.example.com) to _USERNAME_.github.io
2. Create four `A` records pointing `@` (example.com) to:

   ```bash
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

   e.g. Completed setup for [Namecheap](https://www.namecheap.com) (Domain List > Advanced DNS)

   ![Namecheap Advanced DNS settings](/assets/namecheap-dns.jpg "Namecheap Advanced DNS settings")

### On GitHub

1. Navigate to the settings for your site's repo.

   ![GitHub repo settings](/assets/github-repo-settings.webp "GitHub repo settings")

2. On the left, click on **Pages**

3. Scroll down to **Custom domain**, type in your domain/url (example.com), and click **Save**.

## What's all this then?

"**[GitHub Pages](https://docs.github.com/en/pages/quickstart)** are public webpages hosted and published through GitHub." (_GitHub Docs_, 2023)

"**[GitHub](https://docs.github.com/en/get-started/quickstart/hello-world)** is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere." (_GitHub Docs_, 2023)

"**[Namecheap](https://www.namecheap.com/)** is a domain registration and web hosting company."
