---
layout: post
title: "About Pull Requests"
date: 2020-09-24 15:40:36 -0600
categories: code-quality 
---
Whether you’re alone, working closely with a team, or part of a distributed ecosystem working on open source products, you’re codebase evolves by making changes to it. For many reasons, it can be irresponsible to make changes to a codebase directly. Instead, developers create a copy of the codebase, make their required changes, and test their changes locally.

> Pull requests are the mechanism by which a developer asks that the changes they’ve made locally be merged (or “pulled”) into the existing codebase.

Once the pull request (PR) is issued, other developers review the requested changes and approve or deny them being merged into the existing master codebase. If denied, the reviewer may ask for changes to be made. If approved, the new code is merged, and the cycle begins again when it's time to develop another feature.

Issuing and reviewing pull requests is a fundamental part of the development lifecycle, but what makes a good pull request and what makes a good review?

** On Submitting Pull Requests

*** Keep it short
Everyone is willing to spend some amount of time reviewing a PR. Maybe they can’t say an *exact* number, but there’s a range that falls between feeling like you’ve covered everything and feeling like the review is taking too much time. When the change set is small, it’s easier to hone in on the individual changes and take the time required to review each one.

> Large PRs get reviewed at a macro level. Small PRs get reviewed at a micro level.


*** Constrain the scope
Alongside keeping PRs small is keeping them focused. 

*** Automate the easy stuff

** On Reviewing Pull Requests
