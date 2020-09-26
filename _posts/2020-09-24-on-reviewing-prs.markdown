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

## On Submitting Pull Requests

### Keep it short

Everyone is willing to spend some amount of time reviewing a PR. Maybe they can’t say an #exact# number, but there’s a range that falls between feeling like you’ve covered everything and getting fatigued enough to just push it through. The latter can easily result in code getting merged in that shouldn't. When the change set is small, it’s easier to hone in on the individual changes and take the time required to review each one.

> Large PRs get reviewed at a macro level. Small PRs get reviewed at a micro level.

That being said, some changes are big and issueing a PR with a completed version of the feature/ticket will result in a large set of changes. For this particular problem, keep in mind that it may be a symptom of not breaking down features into small enough pieces during the planning phase.

Assuming that's not the case, it's a good idea to create a parent branch for the feature, then issue work-in-progress (wip) pull requests to your parent branch as you finish key peices of the feature. Once everything has been completed, you can issue a pull request from your parent branch to the master branch with the knowledge that all the peices have been reviewed along the way.

### Constrain the scope

Alongside keeping PRs small is keeping them focused.

### Automate the easy stuff

## On Reviewing Pull Requests
