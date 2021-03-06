---
layout: documentation
title: Who is a Maintainer?
date: 2017-08-14
doctype: general
---

> From Wikipedia - Maintainer is usually one or more people who build source code into a binary package for distribution, commit patches, or organize code in a source repository


`kubicorn` is a small team currently, things are evolving at a very fast pace. We need more people, who can really help grow the community and help get the project production ready. If you are new to opensource, just introduce yourself to the community and get started. For `kubicorn` it can be any person who is willing to take these responsibilities.


## Easy to say, hard to do, lets break down tasks for a maintainer:
 
 - Strive towards getting `kubicorn` to be production ready.
 - Work with community to:
    - keep the code base stable
    - perform code reviews
    - triage bugs
    - create releases
    - resolve conflicts
    - research what's best for the community.
 - Work with other maintainers to keep the project growing and stable.
 - Avoid having too many API changes, if necessary it should fulfill [backwards-compatibility-promise](http://kubicorn.io/documentation/semver.html)
 - Don't say Yes unless you are 99.999% (there is nothing 100%).
 - Remember, you are not alone, there are people to help you as well.
 - Take a break, whenever you need.


## Criteria for code merge:
 - Maintainer(s) of the repo can merge code, with at least 2 LGTM.
 - This is mostly Golang code. If golint, gofmt is not done - DON'T merge, follow guidelines here [CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments)
 - Look for unit-tests, it is important (try not to merge with TODO unit-test, that just means forget about it).
 - Of course the builds have to be passing.

### Current Maintainers:
- [Kris Nova](https://github.com/kris-nova)
- [Marko Mudrinić](https://github.com/xmudrii)
- [Prateek Gogia](https://github.com/prateekgogia)
- [Robert Bailey](https://github.com/roberthbailey)
