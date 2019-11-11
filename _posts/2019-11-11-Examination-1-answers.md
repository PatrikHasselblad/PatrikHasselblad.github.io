---
layout: post
title:  "Examination 1 answers"
date:   2019-11-11 04:57:03 -0600
categories: jekyll update
---

### What I think about pre-compiling my CSS.

To be able to divide my CSS code between pages makes it easier to organize and to quickly find what I am looking for. 
However, beside dividing, there weren’t really much more to it. Mixins I can imagine being of great use if we build a 
big site, but for a smaller one like this I found I actually had to write more code for it. But at some points it made a lot of sense.

I used the 4 minima sass files as a foundation for my work. Not because it was the easiest way out but because it gave me a lot of 
ideas and help when I was trying to make my site look good.

I usually sort my CSS code according to the html-tags on the pages. To make this pre-compiled CSS any useful I had to divide it 
somehow and that made things a tad messy. The nestling, however, was a really nice addition and made it a lot easier to read.

### What I think about static site generators.

I love SSG. It was actually alot of fun making this site. First I had to spend a few days figuring out where to actually write things 
and where to put my own layout so it actually changed the site.
I can imagine quite a lot projects SSG is suitable for. For starters, a blog, is a very good project to use SSG for. I can’t really figure 
out any project it would be bad for, but I am sure there are a few. I can imagine working with a lot of security mechanisms can make 
it more difficult with an SSG, but with enough experience I am sure issues can be solved.

The best thing with SSG is that I really didn’t have to write any HTML code at all, I am fairly new to HTML and CSS so I still think 
it is quite fun to write it, but this way I will still enjoy it!

### About my Robots.txt

A robots.txt file is used to give robots instructions. There are a lot of different robots. 1 such is for example googles search robot that 
will index my page so people later on can search my name and find this delicious site. There are also spam-robots that search the internet 
for email addresses for the purpose of spamming our e-mails with commercial, really bad emails and so on.

I did a very basic robot configuration. I allow googles robot to visit my page but disallow every other robot, that cares to read my 
robots.txt file that is. Perhaps I change this later on when I find it to be necessary.

### About my humans.txt

Humans.txt is a file that explains the persons/humans behind the site. Many companies does not want this printed out on the site, therefore, 
we add it in a small and easy-to-access txt file.
My humans.txt doesn’t really contain all that much since I am the sole developer. I included my earthly location and a fake e-mail address 
that points to the blog discuss department. I also included some thank you notes and some information about the site, such as when 
it was last updated & what software I used.

I also linked the file to the humans.txt button in the footer of the site.

### How I implemented comments to my blogposts.

I created an account on disqus.com and followed the instructions on the site. From there I got a bit of code to copy/paste in one of my 
HTML-files. I pasted it on a suitable location in my layout page for posts, that is generated each time I add another post. 
That way I don’t have to do anything further for it to work in the future. It will always pop-up, down below on each page.

Before I could figure out how to make it work I published my website through [github.com](https://github.com/){:target="_blank"} because I thought I needed the 
actual address for the site. It turned out that was not the case, but it is more fun to see the little product evolve online as well, 
so I don’t cry overly much.

### Open Graph and how I made use of it.

Open Graph is a more detailed hyperlink. It adds a bit of information about the site that is linked to. It was developed by Facebook, but today it 
is more or less standard to implement. It adds a little box of information below the link.

I added the Open Graph protocol in my meta-tags of my head-section. It was somewhat difficult to know if it worked or not, so I added googles 
“open graph checker” to my browser just to be certain, and it worked. My Open Graph give information such as my name and a short description of the site.
