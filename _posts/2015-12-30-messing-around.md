---
layout: post
title: "Messing Around"
description: "Some ramblings about setting up Jekyll Bootstrap"
category: "rambling"
tags: ["blogging"]
---
{% include JB/setup %}
# Welcome to Jekyll Bootstrap - I Think
A friend of mine has been looking for a simple blogging platform that is friendly to technical writers who want to display code snippets & whatnot.  I stumbled across the tool named Jekyll which is apparently the base for static pages hosted on GitHub Pages.  Jekyll is great, but it requires a good bit of web developer/designer chops to get setup just right.  In an effort to find something that shielded me from all the web developer/designer stuff I wasn't interested in I came across Jekyll Bootstrap which seems to scaffold a lot of that for me.

## What do I Want to Do?
Well, quite simply, I just want to do some simple blogging with a plain text editor (like my favorite, Vim) and manage the whole thing with Git.  I also don't want to be bothered with hosting my own server and managing all that.  Finally, I'm incredibly cheap so free appeals to me a great deal!

##Here's Some Code
Here's a little bit of GPIO Zero for all the haters out there...
```
#!/usr/bin/env python

from gpiozero import LED

led = LED(17)

led.on()
led.off()
```
