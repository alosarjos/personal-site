---
title: Hello Astro
layout: ../../../layouts/BlogPostLayout.astro
author: José Miguel Sarasola
description: "Hello Astro"
image:
  url: "/blog/astro-logo.png"
  alt: "Astro logo"
pubDate: 2022-11-14
tags: ["astro", "blog"]
---

The site is back! And with a new and shiny framework! Now, the framework may be good but my frontend and design skills ain't, but still can talk about how is to build an Astro project as someone who is not a frontend developer.

## No JavaScript in a JavaScript world

This is by far to me one of the best features of Astro, while it allows to use JavaScript frameworks for required tasks, it's more like a plugin in case you need than a first-class citizen. The logic around the site creation is written in Astro's own language and built into a completely static multi page applicaction site, giving you the user, no JavaScript at all (On this site at least).

The project, not counting the **.astro** files actually contains just 2 **JS** files just with config exports for Astro and Tailwind. Pretty neat.

## You get a plugin! And you get a plugin! And you get a plugin!

Astro allows building on top of it using the most popular JS frontend frameworks. I'm guessing that allows them to sell it better to *anyone*, but I'm more of using a tool designed for one thing for that single thing. In my case, where I want to deploy a static site with Markdown written blog entries, seemed like a nice choice, but in case I needed something more interactive I would probably choose another tool like **Next.js**.

## A short entry for a new blog

You can find the source code for this blog on [GitHub](https://github.com/alosarjos/personal-site). Do not expect frontend or design best practices though.

See you next time