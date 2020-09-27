+++
title = "Week of 21 Sep - 27 Sep"
date = "2020-09-27"
author = "Shrivu Shankar"
cover = "/img/head.jpg"
description = ""
+++

### What did you do this past week?

This week I met with my team and started work on the project. So far I'm about 60% complete and most of the big tasks are done.

### What's in your way?

My last assigned task for the project is the dynamic stats on the about page. It shouldn't be too bad since GitLab has an API, but still thinking of a good way to dynamically count unit tests.

### What will you do next week?

Finish the project in the next few days and then start the midterm grind.

### What was your experience of types, object models, and iterators?

It's interesting to see how the designers of Python choose what to keep (from other languages) and what to change when creating the types. Compared to [Javascript](https://javascriptwtf.com/) they did a great job with making the types intuitive. One thing that bothers me is that Downing taught the class that Python sets use bucketing internally and `.remove()` has always constant complexity, however both of these are [provably incorrect](https://piazza.com/class/kdm1crxn32e6dm?cid=127).

A question posed in class was why Python uses an exception to signal the end of an iterator, according to [PEP234](https://www.python.org/dev/peps/pep-0234/) it is a more performant design.

> It has been questioned whether an exception to signal the end of the iteration isn't too expensive ... Calling an end() function would require two calls per iteration. Two calls are much more expensive than one call plus a test for an exception. Especially the time-critical for loop can test very cheaply for an exception.

### What made you happy this week?

I was able to buy my first [chicken shawarmas over rice](https://thehalalbros.com/menu) using (effectively) free bitcoin that I mined last week. I was thinking about upgrading my mining setup but I think if I draw anymore power my apartment people may start to notice.

### What's your pick-of-the-week or tip-of-the-week?

I've been using [DigitalOcean](https://www.digitalocean.com/) a lot this past week and it's such a great way to spin up cheap servers for quickly testing and running misc scripts. You can pretty much just click a button and you immediately get an IP address that you can SSH into and do whatever you want. Their cheapest tier is also only `$5`/mo which is amazing.