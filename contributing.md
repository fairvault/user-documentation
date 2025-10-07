---
layout: page
title: Contributing
permalink: /contributing/
---

# Contributing to This Site

We welcome contributions! You can add new pages, improve existing ones, or share posts.  
Here’s how to get started.

---

## 1. Fork & Clone

1. Fork this repository to your own GitHub account.
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/{{ site.baseurl | remove:'/' }}.git
   cd {{ site.baseurl | remove:'/' }}
   ```
3. Or edit directly on Github.
   
## 2. Add a new page

```
---
layout: page
title: New Page
permalink: /new-page/
---
```

# My New Page

Write content in **Markdown**. Jekyll will automatically convert it into HTML.

## 3. Add a Blog Post

Posts go inside the _posts/ folder. Name them like this:

`_posts/YYYY-MM-DD-title.md`

