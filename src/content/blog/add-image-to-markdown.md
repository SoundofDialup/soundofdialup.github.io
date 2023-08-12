---
title: Add an image to a markdown file
author: Sound of Dialup
pubDatetime: 2023-08-12T09:10:34.188Z
postSlug: add-image-to-markdown
featured: false
draft: false
tags:
  - markdown
description: How to add an image to a markdown file.
---

Today I learnt how to make markdown images more accessible with alt text and a title.

## Table of contents

## Instructions

**Syntax:**

```bash
![alt text](image url "image Title")
```

**Example:**

I want to add a screenshot of my project's directory structure. The markdown file and image are in different folders (i.e. the image is in `instructions/assets/` and the markdown file is in `instructions/markdown/`).

```md
![Screenshot of a project tree in VSCode, showing a parent folder, 'instructions', and two child folders, 'assets' and 'markdown'](../assets/vscode-project-tree.jpg "VSCode project tree")
```

**Result:**

![VSCode project tree](/assets/markdown-add-image.jpg "VSCode project tree")

## What's all this then?

**[Markdown](https://www.markdownguide.org/)** is a "simple and easy-to-use markup language you can use to format virtually any document." (_Markdown Guide_, 2023)

"**[Visual Studio Code (VSCode)](https://code.visualstudio.com/learn)** is a free coding editor that helps you start coding quickly. Use it to code in any programming language, without switching editors." (_Microsoft_, 2023)

`../` is a relative path reference. Here's my **[guide](/posts/relative-paths)** on those.
