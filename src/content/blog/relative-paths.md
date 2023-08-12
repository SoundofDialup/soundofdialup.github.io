---
title: What are relative paths
author: Sound of Dialup
pubDatetime: 2023-08-12T23:10:34.188Z
postSlug: relative-paths
featured: false
draft: false
tags:
  - webdev
description: How do web devs reference different folders within a website?
---

What's all this `/`, `./`, and `../` gobbledygook?

## Table of contents

## Reference

```bash
my-project/
├── js/
│   └── main.js
│   └── utils/
│       ├── test.js
│       └── login.js        👈 WE'RE STARTING HERE
├── README.md
└── index.html
```

| Path  | Target                    | Example                      | Direction                  |
| ----- | ------------------------- | ---------------------------- | -------------------------- |
| `../` | Parent directory          | `"../main.js"`               | _login.js_ 👉 _main.js_    |
| `./`  | Current working directory | `"./test.js"` or `"test.js"` | _login.js_ 👉 _test.js_    |
| `/`   | Root directory            | `"/"` or `"/index.html"`     | _login.js_ 👉 _index.html_ |
| `/`   | Root directory            | `"/README.md"`               | _login.js_ 👉 _README.md_  |

```html
<!-- Link to take user to homepage (version 1) -->
<a href="/index.html" alt="Back to Home"></a>

<!-- Link to take user to homepage (version 2) -->
<a href="/" alt="Back to Home"></a>
```

```js
// Reference a function in main.js (from login.js)
import { myFunction } from "../main.js";
```
