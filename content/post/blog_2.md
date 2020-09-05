+++
title = "Week of 31 Aug - 6 Sep"
date = "2020-09-05"
author = "Shrivu Shankar"
cover = "/img/head.jpg"
description = ""
+++

### What did you do this past week?

This week I started work on the collatz project. I've made it to step 8 in the workflow and so far so good. After a year of avoiding the pain/weirdness of install Docker on Windows, I finally got it to work!

### What's in your way?

I incorrectly assumed that I'd have significantly more time with classes online so I signed myself up for a lot of things to do (classes, clubs, research, etc), but it looks like I might have overdone it. As of writing this, I have a full kanban of due-before-monday tasks in the way of working more on the project.

### What will you do next week?

My current plan (hope) is to finish the project by the middle of next week. It seems like the biggest part that's left it just the optimizations and that doesn't seem to bad, but I won't know for sure until I submit against the hackerrank.

### What was your experience of assertions, unit tests, and coverage?

I thought it was a bit weird that we/Downing are against "asserts" for unit tests but the way we write our unit tests in the lab is with `self.assertEqual`, which is itself an assertion. It seems we're not really against "asserts" but really the use of the python `assert` keyword for testing (this seems analogous with how `panic` is used in other languages). Coverage has always seemed like magic, I'm very curious how it's determing which lines of code are running under-the-hood. I know Python has a pretty rich meta API so it's probably tapping into that.

Edit: I looked it up in the [coverage docs](https://coverage.readthedocs.io/en/v4.5.x/howitworks.html). Coverage attaches itself to the Python interpreter with `sys.settrace` and then records all the line numbers and line jumps that occurred. From there it can just post-process that data to determine the coverage statistics.

### How are you doing and holding up? What's been most helpful for you in terms of support at this time?

It feels too early in the semester to be already grinding, but setting a personal work-curfew and carefully tracking tasks with [Notion](https://www.notion.so/) seem to be working alright so far.

### What made you happy this week?

I got a intern offer at a pretty cool company and if I needed to I could finally stop recruiting now.

### What's your pick-of-the-week or tip-of-the-week?

I recently switched from the builtin terminal on Windows to [Fluent Terminal](https://www.microsoft.com/en-us/p/fluent-terminal/9p2krlmfxf9t). It's super fast, clean, and allows you to have different terminal shortcuts that are pre-configured to the environment of a specific project. I have it setup now so that I can just click a single shortcut on my desktop and it opens vscode + explorer + relevant web docs + a pre-configured terminal which I'm thinking will save a bunch of time in the future.