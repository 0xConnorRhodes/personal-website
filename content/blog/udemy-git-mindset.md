---
title: "Git Mindset Course on Udemy"
date: 2022-11-15T11:35:50-06:00
draft: true
---

I recently completed the [Git Mindset course](https://www.udemy.com/course/git-mindset/) from Abhin Chhabra on Udemy. This course was my first systematic intro to the inner-workings of git, and it was very valuable. I've been using git for personal projects for a couple of years now, but I recently had the opportunity to write some internal tooling as part of a team at work. This put me in a situation where I needed to be comfortable creating branches, merging changes, and resolving merge conflicts on a regular basis. I quickly realized that I didn't understand git's particular terminology (HEAD, objects, refs, etc.) well enough to understand the man pages and conceptualize everything I was doing.

Git Mindset is a different sort of git course than many others on the market. Most courses (including ones I have completed before) give a series commands to memorize by wrote. Git Mindset, on the other hand, gives you a mental model of how git's distributed architecture works using a simplified dev team scenario as context for why git is built the way it is. The course delves into how the `.git` directory functions and provides illustrations of the key terms in the git manual so you can rely on git's own documentation for your future reference.

I think the most valuable part of this course for me was learning to visualize git's commit graph across different branches, and learning how to represent the graph with `git log --graph --all`. Understanding that git's core data structure is a (tk-verify, directed acyclic graph) and being able to see where each commit falls on that graph allows me to understand what operation I need to perform to leave the team's repo in the state we want.

The one area where Git Mindset falls short is that it does not cover how to rebase, which is a common operation in most team development. That being said, I would highly recommend Git Mindset for anyone who is getting started using git for team development. You can start with a short course that covers common commands by rote such as A Cloud Guru's (tk-link Git Quickstart course) and follow that up with Git Mindset to build a deeper understanding of how Git works under the hood. 

If you want to see where my future studies in git take me, check out my (tk how I learned git page)


(tk tags, git and then a how_i_learned path for the other page referenced above)
