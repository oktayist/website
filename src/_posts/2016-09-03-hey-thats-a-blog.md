---
layout: post
title: Hey, that's a blog!
---

This might look different than it was since two years ago. Well, I finally
updated my website with a new, cleaner style and a brand new blog! In this post
I'll explain a bit more how this was made, and what I will write in there.

### The painful redesign process

I'm not very good at designing things (there is a reason I like backends so
much!), and it took me about a year of iterations to finally get this design
finalized. I made something like five or six different styles from scratch, and
the day after I always said "No, I don't like this at all".

I prefer clean, fast websites than a rich user experience with megabytes of
JavaScript just to show one blog post, and each iteration I simplified the
design even more. This website now has no JavaScript in it, about 120 lines of
uncompressed CSS (and just 23 selectors), no media query, but it still looks
good, both on desktop and on mobile.

### Static generators for the win!

I think the right way to build a blog is to use a static generator: having a
web application generating the same pages for everyone everytime is just a
waste of compute resources, and you can stuff a bunch of static HTML files in a
webserver and get the same result.

There is another advantage of static generators: in most of them, the
"database" is a bunch of text files (commonly Markdown) you can edit however
you like with the editor you want, and you can store the whole website in a git
repository.

There are a lot of static generators out there, and most of them put focus on
creating blogs (like *Jekyll*, *Pelican*, and many more) with a pre-defined
structure. I chose a relatively new one called **Lektor**, which instead tries
to create something you can customize from the ground up.

Other than that, if you don't like playing around with VIM as much as I do,
Lektor provides a great admin UI you can use to edit and deploy the website,
which is perfect for everyone not familiar with text editors or git. [I highly
recommend to check it out!][lektor]

### A peek at the source code

As always, you can find the full source code and instructions about how to
build the website in its [public git repository][github]. Both the source files
and the content of the posts are released under the *Creative Commons
Attribution 4.0* license.

### What I will write there

So, everything is great, I have a new blog, but what I'm going to post there?
Well, sometimes I'll announce something (like new projects), and I'd like
to write down somewhere how I solve some problems with programming or Linux.

I hope I'll remember to post things sometimes (everyone knows I tend to forget
everything, right?). See you soon!

*Pietro.*

[lektor]: https://www.getlektor.com
[github]: https://github.com/pietroalbini/website
