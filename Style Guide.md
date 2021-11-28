<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-MML-AM_CHTML"></script>

# Style Guide

## 1. What is uiuc-cs.xyz?

**[uiuc-cs.xyz](http://uiuc-cs.xyz) is a collaborative [zettelkasten](https://zettelkasten.de/posts/overview/). It is intended to be a comprehensive resource regarding *all* material covered in all CS and CS-adjacent courses, as well as deeper computer science topics not covered by UIUC's curriculum.**

Each page consists of an atomic topic.

> *atomic*: of or forming a single irreducible unit or component in a larger system
> 

For example, a page on linked lists would be an atomic topic. A page on setting up Docker would be an atomic topic. Each page should function essentially as a Wikipedia article. It should be able to link to other pages (see **4. Syntax**) to foster a greater understanding of how topics link together.

Each page is a living document, meaning that it can be updated at any time, most importantly to reflect new content that draws upon its topic. Feel free to make any change that you deem appropriate. For large-scale changes, check with [whatever platform editors use to communicate, likely a Discord server].

The GitHub can be found [here](https://github.com/uiuc-cs-zettelkasten/uiuc-cs-zettelkasten.github.io). 

## 2. User Expectations

If you use this wiki as a resource, you should try to contribute by either creating new pages or updating additional pages with new information or more examples. You can contribute by [TODO: explain git].

## 3. Syntax

### a. Basics

This platform uses [markdown](https://www.markdownguide.org/basic-syntax/), which you may have used in writing a readme file for a project or in some other circumstance. I would recommend reading up on markdown if you're not familiar; it's very easy to pick up.

### b. Linking

To create a link to another page, find the file name in the GitHub repo, and then in your markdown file, type either `[[file-name]]` or `[[file-name|Desired Display Text]]`. To link to another page, type `[Desired Display Text](url)`.

### c. Equations

This platform uses `mathjax` libraries, meaning that we can use a pair of  to insert equations. It uses similar syntax to LaTeX—not sure if they're identical. You can insert them in-line, like this: \\(F_x(x)\\) as `\\( F_X(x) \))`, or you can insert them as a block, like this:

$$r(t) = 100\cos(t)\hat{\imath} + 50\sin(t)\hat{\jmath} + \left(-\frac{162.25t}{2\pi} + 100\right)\hat{k}$$

as `$$ r(t) = 100\cos(t)\hat{\imath} + 50\sin(t)\hat{\jmath} + \left(-\frac{162.25t}{2\pi} + 100\right)\hat{k} $$`. For LaTeX documentation, I'll direct you to [this cheat sheet](http://tug.ctan.org/info/undergradmath/undergradmath.pdf). 

## 4. Page Formatting

To make a page, add a markdown file to the GitHub repository. [To do: tell users where to put the files]

Just like a Wikipedia article, your page should start off with a section defining the topic. Then, it should go over all of the details you've covered in class. Then, it should give some examples, perhaps ones that were covered in class.

## 5. Page Tagging

[TODO: fill this out]

## 6. Non-course content

You should also create pages for CS-related stuff that isn't covered in classes.