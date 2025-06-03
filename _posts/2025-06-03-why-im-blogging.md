---
title: Why I’m Blogging (and Why Jekyll)
date: 2025-06-03
categories: [blogs,meta]
tags: [blogging, ruby, jekyll, chirpy]
---

## Why am I blogging?

I’ve been messing around with a bunch of stuff lately — embedded C, ESP32, FreeRTOS, ROS2, local LLMs, RAG pipelines and I realized that I needed a place to _put it all_.

Somewhere between the `main.c`, the several hundred browser tabs and the horribly named folders, I figured a blog would give me:
- A place to **log what I learn**, before I forget it.
- A reason to **stay accountable** to my side projects.
- A personal space to **geek out** about spacecraft, robots and random 3AM thoughts.

So here we are.

---

## Why Jekyll?

There are a bunch of ways to spin up a blog in 2025. You’ve got Notion, Hashnode, Medium, Ghost, Obsidian + Publish, Astro, Next.js, and probably 5 new frameworks by the time I finish typing this.

But I wanted something:
- **Minimal and classy**
- Static (no backend, no databases, no bloat)
- Easy to version control via **Git**
- Hosted free on **GitHub Pages**

Enter **Jekyll**.

---

## What *is* Jekyll?

Jekyll is a **static site generator**. It takes your plain text files (written in Markdown) and turns them into a complete website.

No JavaScript frameworks. No dynamic rendering. Just HTML, CSS and good old static files.

It just _works_.

---

## What is the underlying stack?

Jekyll is built on **Ruby**. This is all we need to know.

What is Ruby?
 - Ruby is a high-level, interpreted programming language. It is object-oriented, dev friendly and is like Python's artsy cousin.
 - It's primarily used for Web dev (Ruby on Rails framework), scripts, dev tools and static site generators.

What is a "Gem"?
 - It's a library/package in Ruby
 - Distributed via rubygems.org
 - Eg: jekyll. rails. httparty etc.

**Bundler** is a Ruby tool that helps you manage dependencies. You’ll use it to install everything the blog needs via a `Gemfile`.

## Getting Started

Use these concise guides to install Jekyll and its dependencies on your Operating System.
[Installation](https://jekyllrb.com/docs/installation/)

Then, pick a jekyll theme and follow the respective installation instructions. I chose chirpy so I used [these instructions](https://chirpy.cotes.page/posts/getting-started/).

Do some basic configuation changes in _config.yml and you'll be good to go.

## Why Chirpy?

Chirpy is a beautiful, modern Jekyll theme that comes with:
 - Dark mode out of the box
 - Tags, categories, archive pages
 - Built-in support for search, SEO and PWA
 - Syntax highlighting, math expressions and flowcharts
 - GitHub Pages compatibility

It’s perfect for someone like me who wants good design, but doesn't wanna dive deep into frontend every time I write a post.

## TL;DR

This blog is my mission log, a way to track what I’m building and thinking.
I picked Jekyll because it’s fast, minimal, and lets me focus on writing and shipping, not tweaking layouts for hours.

More posts coming soon.

Until then, happy compiling.