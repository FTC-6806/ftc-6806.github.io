---
layout: post
author: Liam Marshall
title: Hello world (how we built this website)!
---

I'm the main programmer this year for our team, and have a bunch of webdev experience, so I got to design our website this year!
By the way, [check the code out on Github](https://github.com/FTC-6806/ftc-6806.github.io) if you're interested.

This is a static site hosted on [Github Pages](https://pages.github.com), which is an awesome, *free* static site hosting service. Since it's static, I used another one of my favorite tools, [Jekyll](http://jekyllrb.com/). Jekyll takes in config files, html templates, and styles, and then lets you write pages and posts in Markdown that get smooshed into the HTML templates.

The thing that's so great about this is that Github Pages will render repositories using Jekyll **on their servers**, so all I had to do to write this blog post was write some markdown on my laptop, and upload it into the `_posts` directory of the repo!
And it's the same for every other page and post.

For all the styling, I started with [a premade theme](https://github.com/jasonlong/cayman-theme), and then added lots of stuff on to it. The blog has styling which is inspired by Ghost's Casper theme, and the navbar is a custom, flexbox-based library I wrote.
Everything was done using SCSS, which Jekyll will compile too!

The fonts are Roboto (the Google font), and Audiowide (for the heading).

Everything is copyright Team 6806 Ratchet Robotics, if you want to reproduce material, [contact us]({{baseurl}}/contact)
