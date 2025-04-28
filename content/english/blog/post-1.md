---
title: "First test with Claude Code"
meta_title: ""
description: "this is meta description"
date: 2025-04-27T05:00:00Z
image: "/images/image-placeholder.png"
categories: ["Application", "Data"]
author: "Jie Wu"
tags: ["nextjs", "tailwind"]
draft: false
---

Today I tried to install Claude Code and made a [web app](https://dnageek.github.io/calendar.playground/), it was fun. Here are my steps and take-aways:

## Steps I've taken

* Started an EC2 t3.medium instance, all settings are default
* Install Claude Code as instructed by its manual
* Start to prompt within claude code to build the app
* of course, track the folder in github and host the web app on github.io

All straightforward, just follow their documentations

## Take-aways

* With Claude Code, from scratch, I was able to build a working app  with three functions within a few hours and a few bucks!
* I am new to building web apps with javascript, or using openai api, or using puter.js (never heard of it until today), but it didn't seem to matter
* I do need to break down the tasks into smaller pieces, sometimes give clear directions, for example:
    * explictly asked Claude Code to study the chat function from Puter.js to make sure it understands the function
    * went in the log to figure out the exact error, and then taught Claude Code the structure of the return value of the chat function
* The cost was about 7 bucks, but it will stack up quickly if the code gets fat!

