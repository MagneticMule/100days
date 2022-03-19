---
title: Day 001
date: "2022-03-19"
description: "Oh, big first day of my 100 days of code"
---

## What did I do?

So yeah, I took the easy option here. I created a Gatsby based blog based off the now infamous [Gatsby blog template](http://example.com "Gatsby Blog Template"). I knew I needed a private (yet cheekily public) space to record my progress each day and I knew that I didn't want to write on something like [Dev.to](https://dev.to/ "Dev.to") as to be brutally frank I am doing this purely for me. I am not interested in feedback (as of yet) or critical discussion on the minutiae of dev tools. So, a simple Gatsby based blog it was. Also, I liked the idea of everything being hosted on Netlify that is tied to a Github repo with all blog entries being housed in simple MarkDown files. Suits me.

## How did I do it?

Well, I already had Gatsby and all it's dependencies installed via NPM. I am using WIndows on my main machine as I get tired of Apple and it's flakey machines. However, I can't say I enjoy Windows as a Dev environment, it's good for games though. Powershell is a poor replacement for a good old ZSH command line but I digress.

Starting a new Gatsby site with a standard blog starter is simple.

`gatsby new gatsby-starter-blog https://github.com/gatsbyjs/gatsby-starter-blog`

There are a wealth of [Gatsby Starters](https://www.gatsbyjs.com/starters/? Gatsby Starter Templates) you can use to get started but I picked the first one I found. I don't have the time to mess around too much here so keeping things simple is a central concern.

I didn't do a great deal to the starter template, just changed the favicon and bio. I may come back and change things later but I need to get this thing up and out the way.

After I deleted and created my first blog post (the one you are reading here) I made a new [GitHub repo](https://github.com/MagneticMule/100days.git Github repository for this blog here that you are now reading) to store this thing. Then committed the blog to the new repo.

```
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MagneticMule/100days.git
git push -u origin main
```

All well and good but I still needed some hosting. I have been using Netlify for a year or two to host a couple of client projects and it has been more than fine. Hell, it's fast, fun and free (within reason).

Creating a new site was as easy as pointing Netlify to my new blog repository, waiting until Netlify did it's build magic then bam! A new site is live.

## What did I learn?

For me, the purpose of 100 days of code is to focus on learning one thing a day or at least discovering something new. Tb be frank, I didn't learn much with this project. I already know GatsbyJS reasonably well and have used it for two client projects (yes, paying clients). However, as is the case with much of my dev practice I am rusty. Here I get a chance to write in MarkDown each day, something I haven't done since 2005.
