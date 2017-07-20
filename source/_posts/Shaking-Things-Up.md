---
title: Shaking Things Up
subtitle: A new look portfolio
date: 2017-07-17 19:11:49
tags:
- portfolio
- blog
- hexo
- node
- code
---
It's been a long time coming, but I have finally got around to a full overhaul of my personal site. With this first post I just want to talk about how I've done this revamp and where I plan to go from here.
<!-- more -->
## The basics
Those who know me have undoubtably heard for years that I've wanted to completely change things, hopefully this is a step towards continuous improvement on it! My old site was built in a few hours with just some basic code and light scripting, nothing fancy really. I never felt it was up to par with my work for clients. With this new look I took a long time considering what framework I wanted to use as well as what I wanted to include in terms of content. I finally decided a blog would be great to add in on top of just a portfolio, and I thought it would help me grow as a developer as well.

I do a lot of work in [WordPress](https://wordpress.org/) so that was an obvious candidate to build this with, but if you know me you also know I love to learn new frameworks and technologies. I scoured the web and came across [Hexo](https://hexo.io/), which really caught my attention. This allowed me to use [Node](https://nodejs.org/en/) which in my opinion is much easier to use and gives me a much richer toolset to accomplish my goals. With Hexo, rather than using a database like WordPress, it is a static site generator so while everything on this site is quite customizable, in production nothing is dynamic.

## Nuts and Bolts
So I've choosen my framework, now what? Similar to WordPress, the Hexo front end also uses [themes](https://hexo.io/docs/themes.html). To no ones surprise, I decided I wanted to design and create my own theme that I will release (once I've put in some more polish) for anyone to use! Beyond the docs, I also started with a [great tutorial from Jonathan over at CodeBlocQ](http://www.codeblocq.com/2016/03/Create-an-Hexo-Theme-Part-1-Index/) and obviously deviated from the tutorial as needed. His tutorial really helped me get a good understanding of how everything works together in Hexo.

So I jump in, first thing I see is a filetype I've never used before, '.ejs' which is [Embedded JavaScript](http://www.embeddedjs.com/). This is really where the power in Hexo lies. I'm able to put in customizable content all around the site, then once I am ready I just generate the code and everything is ready for the live site! It does remind me a lot of the front end with [Angular 2](https://angular.io/) but I'm sure there's tons of similar frameworks out there (I'll learn them eventually maybe).

## Technologies
I do want to point out a few people I borrowed code or ideas from here.
- [Disqus](https://disqus.com/) - Comments engine for the site
- [Font Awesome](http://fontawesome.io/) - for all the icons which I love
- [Vecteezy](https://www.vecteezy.com/vector-art/106872-free-vector-tree-tops) - I'm not quite talented enough to create all my own graphics, these are the trees in the header
- [Eucalyp at the Noun Project](https://thenounproject.com/search/?q=pcb&i=1116666) - This is the circuit graphic on the front page. I did some things with the color.
- [Iconfinder](https://www.iconfinder.com) - For the rest of the icons and graphics
- [Formspree](https://formspree.io/) - This very useful service handles my contact form
- [Animate on Scroll Library](http://michalsnik.github.io/aos/ "AOS Github") - Really fantastic library for animations and it couldn't be easier to use.
- [Koala](http://koala-app.com/) - My preprocessor for compiling my [SASS](http://sass-lang.com/) stylesheets.

I also decided to try out [Adobe Illustrator](http://www.adobe.com/products/illustrator.html) for the first time which I used to finish up the banner. I may have forgot something and if I do I will definitely come back and add it in an edit! Most of the rest I did from scratch. I've been continually working on my own grid system, which is far from perfect, and it is helping me learn a lot as I do it. I've also learned more about the [flexbox](http://cssreference.io/flexbox/) over this which has been helpful for positionings and responsiveness.

## Where To From Here
There are still a lot of things I want to do with the site and I'm sure I'll never be quite satisfied. I still think the mobile side needs some love, but I am only a little ashamed of where it stands now. Also at some point migrate over to git hosting which will make it easier for me to post updates. Hopefully if anyone comes across bugs, issues or just generally thinks my design looks terrible, you can let me know so I can improve!

If you are still with me, I'm so sorry you had to read all of this. I really wanted to do a comprehensive article just about what I've done here. My goal is to post here regularly, once a week if possible (and if I can think of something to say) but once a month at least! So check back often, and happy coding!