---
title: Using this site
tags: [formatting]
keyords: notes, tips, cautions, admonitions
last_updated: March 27, 2018
layout: page
summary: "Using this site for regulated  documentation  "
permalink: whythis.html
---
{{page.title}}
{: .w3-xlarge}
{{page.summary}}
* TOC
{:toc .wwg-button .w3-light-grey}


http://sphinxtechnicalwriting.readthedocs.io/en/latest/#
Using RegTest for regulated documentation

This website is mostly a tutorial on how to set up Sphinx for continuous deployment with totally free software.

The setup presented here is great to solve the following problems:

    You are the only tech writer of your company and cannot keep up with the software production (1 TW for 6+ dev teams)
    You must wear the PM hat, the tech writer hat, and the QA hat, and want to automate the QA part.
    You want to enable developers to contribute to the docs.
    You still want to have full control over the docs to steer it in the right direction.
    You want to be able to write the docs too, or fix other contributors’ documentation.
    You do not want to break the bank with licenses.

The solution uses GitHub, Travis CI and Sphinx but if you are using different tools, like Bitbucket and Jekyll, or a local setup of Git and Hugo, the examples should still be meaningful.

Before I created this setup, I looked for information and it turned out that it is difficult to find information about Sphinx that comes from technical writers.

In order to fill this gap, I decided to create this website to share some tips and tricks that, hopefully, will be useful to some of you, fellow tech writers.

To see why I think Sphinx is one of the best generators (in my context), refer to Sphinx features for technical writing.

To see how to set it up for continuous deployment, refer to Continuous deployment.

Finally, if you are really new to modern technical writing based on lightweight markup languages and static website generators, here is a quick recap.
A recap on modern technical writing

What’s a static website generator?

It’s a piece of software, generally free, that turns text files into a simple website. Generators are generally open source, so you can modify anything, or use other people’s modifications (extensions). Most importantly, it’s great because it’s fast and simple. And you know… less is more.

Why would you do that, some software is designed to write docs like MadCap Flare, oXygen, etc?

This kind of software works, but you depend on a heavy architecture that is generally slower, and harder to customize. They can even use a proprietary format, so migrating to another system becomes really hard
