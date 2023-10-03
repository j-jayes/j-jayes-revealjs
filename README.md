# Purpose

I love reveal JS - I think it's great. Here is my personal theme. You can look at a [live demo here](https://rawcdn.githack.com/j-jayes/j-jayes-revealjs/07c15a79bc99cbdaa25b757f18d4a8577b824b9a/template.html)

## Origin

I have adapted this theme from the one crafted by [Jonas](https://github.com/pjkreutzer/pjk_theme_revealjs) and [Grant McDermott and Kyle Butts](https://github.com/grantmcdermott/quarto-revealjs-clean-demo)

## Installing

```bash
quarto use template j-jayes/j-jayes-revealjs
```

This will install the extension and create a template for a presentation.

To use the template with an existing presentation use

```bash
quarto install extension pjkreutzer/pjk_theme_revealjs
```

## Using

```yaml
---
title: A title
subtitle: A subtitle
format:
  j-jayes-revealjs-revealjs: default
author:
  - name: Jonas Kreutzer
    orcid: 0000-0000-0000-0000
    email: alias@email.com
    affiliations: Your Institution
date: last-modified
---

```

Further extensions can be listed underneath the theme extension.

```bash
format:
  pjk_theme_revealjs:
    attribution: true
```
