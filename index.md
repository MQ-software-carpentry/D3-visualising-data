---
layout: page
title: Visualising your data on the web using D3
---

**Instructor:** Xavier Ho

**Contact:** xavier.ho@data61.csiro.au

**Etherpad:** <http://pad.software-carpentry.org/ResBaz2018-D3>

Open science should be visible science. What better way is there to make your 
research visible and accessible than to put it on the internet. However, no one 
wants to read endless tables of data. We’d rather look at graphs, or, even 
better, have the possibility of interacting with the data. And we have probably 
all created some graphs. But in order to make them  accessible to many people, 
we will have to move away from our specialized software to a more universal 
platform: the internet. 

We want to:

* Display our data on a website to increase visibility and accessibility of our 
  research.

Our goal is to create a [dynamic bubble plot](http://bost.ocks.org/mike/nations/) (a prettier version of a scatter plot) and publish it on the internet.

Along the way, we will learn:

* how to create our first own web page
* how to change the appearance of certain elements on the page
* how to integrate graphical elements into our page
* how to publish our page 
* how to allow interaction with elements
* how to store data for the use in webpages
* how to create a graph in D3

> ## Prerequisites {.prereq}
>
> * Github account and Github client for your operating system (Windows, Linux, iOS).
> * Participation in at least one SWC workshop.
> * Familiarity with at least one programming language: concept of loops, functions, and conditionals.
> * Familiarity with your favorite text editor (Sublime Text is a good option).
> * You will need to be comfortable with search engines! 
> * Preferably Chrome or Firefox(because of its excellent developer tools).

> ## Setup {.prereq}
>
> * It's probably a good idea to install a GitHub client, if you are not already
> * comfortable with commandline git.

## Topics

1.  [HTML](01-html.html)
2.  [CSS](02-css.html)
3.  [Images and SVG](03-images-and-svg.html) 
4. 	[Publishing with Github](04-publishing-with-github.html)
5. 	[JavaScript](05-javascript.html)
6.	[JSON data format](06-json.html)
7.	[D3 Setup](07-d3setup.html)
8.	[D3 Into the data](08-d3enter.html)
9.	[D3 Add and remove](09-d3exit.html)
10. [D3 Transitions](10-d3update.html)
xx. [What now?](xx-d3future.html)

We are using [gapminder data](http://gapminder.org) and the later lessons are 
based on an example by [Mike Bostock](http://bost.ocks.org/mike/nations/). 
In order to make this example slightly easier, we interpolated the data. The 
data files can be found [here](https://github.com/IsaKiko/D3-visualising-data/blob/gh-pages/code/nations.json).

Lessons created by [Isabell Kiral-Kornek](https://github.com/isakiko) and 
[Robert Kerr](https://github.com/robrkerr). Course upgraded to v4 and v5 by 
[Xavier Ho](https://github.com/Spaxe).
