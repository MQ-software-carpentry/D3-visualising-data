---
layout: page
title: HTML
subtitle: Making things appear in your browser
minutes: 20
---

> ## Learning Objectives {.objectives}
>
> * Create your first web page and view it in a browser
> * Understand the structure of an HTML document
> * Understand the different elements within an HTML document

A way of writing that is understood by all web browsers is HTML:
hypertext markup language. Since we don’t have the ability to do
logical operations (loops, etc.) with HTML alone, it’s
not technically a programming language.

Let’s see how we can get our browser to greet the world. We need to:

* Create a local folder `gapminder_datavis`
* In the folder, create the file `index.html`
* Open the file with a text editor

Now, if we want to open our new file in a browser, we have to tell it what kind of
file to expect. To do this, we start our file with:

~~~ {.html}
<!DOCTYPE html>
<html>
	<!-- Everything goes in here -->
</html>
~~~

Comments (ignored by the browser) starts with `<!--` and ends with `-->`.

Every good webpage consists of a head and a body.
The header (`<head>` to open and `</head>` to close) normally
contains any meta-data. This could be name of the page or
the inclusion of other files.

The body (`<body>` to open and `</body>` to close) is where all our content
should go. So everything we type between the brackets will be displayed
on our page.

~~~ {.html}
<head>
</head>
<body>
	Hello, world!
</body>
~~~

Since our browser understands this language, we can instantly
open our local index.html file and the browser will interpret our
code as visual components.

HTML has more predefined elements that will vary in size and style.
To divide the page into different section, we can create a division
using `<div>` to open and `</div>` to close it.

~~~ {.html}
<!DOCTYPE html>
<html>
	<head>
		<!-- meta-data (like page title, inclusion of other files) -->
	</head>
	<body>
		<div>Hello, world!</div>
		<div>Hi world, I'm dad!</div>
	</body>
</html>
~~~

HTML offers many useful typographical elements. Here are a few common ones:

 * `<h1>`, `<h2>`, and so on
 * `<strong>` and `<em>`
 * `<blockquote>` and `<pre>`

We can also insert a title for our browser page, as below:

~~~ {.html}
<!DOCTYPE html>
<html>
  <head>
    <!-- meta-data (like page title, inclusion of other files) -->
    <title>My first webpage!</title>
  </head>
  <body>
    <div><strong>Hello, world!</strong></div>
    <div><em>Hi world, I'm dad!</em></div>
  </body>
</html>
~~~

Try the following tasks to make yourself more comfortable with HTML. You will
find the search engine useful if you are not sure how to do it. Feel free to 
ask for help!

> ## Your turn: Getting the webpage started {.challenge}
>
> 1. Create a heading for the page, and call it "The Wealth & Health of Nations".
> 2. Make the heading in italics. 
> 3. Credit Gapminder data by creating a hyperlink back to their website. Use
>    the text "Data source: Gapminder". 

Useful resources are also the [MDN documentation](https://developer.mozilla.org/en-US/) and [w3school](http://www.w3schools.com).

You are also encouraged to use the Developer Tools in your browser (Ctrl+Shift+I
on Windows, or Cmd+Options+I on MacOS) to inspect sources of HTML and see how
others work.

Another way to get to the Developer Tools is right-click on any element on the page and select 'Inspect element'. It should open and you should be in the 'Elements' tab. Here, you can navigate through the HTML file and inspect properties at the same time.
