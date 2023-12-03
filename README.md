# Notes
# Lesson 1 - Week 0

## HTML, CSS, JS, DOM

Easy Things:
Tags, attributes, inline styles, JS Basics

Advanced Things:
External Styles, classes, ids, flexbox, JS ↔ HTML (selectors, DOM) connection, Chrome Dev Tools

Create a portfolio returns calculator in JS for the Zerodha Clone we are building

### How do browsers render websites?

Needs to allow people to hit a specific url server and rendered the html, css, js on our screen.
Its job is to render it.

### Why only HTML, CSS, JS?

It can understand more things but the use of HTML, CSS, JS were set in stone long ago and they serve all needed purposes so we let it stay. Literally everything you see on the web can be written in the above 3.
The most we use is JS and its Frameworks.

## HTML Basics

Defines the structure of our website: what is placed and where it is placed.

Things we need to know: 1) Tags 2) Attributes

You could just type text in your .html and it would display what you want but only if you use tags will you be able to understand how you can move stuff around.

- \<div>: Means → one division/line of your page, if too long the text overflows into the next line.
You need to close every <div> tag with a </div> tag (not only div but any tag needs a closing).
YOU CAN NEST DIVs.
- \<html>: place to put html code (added by default, so no biggie)
- \<head>: all metadata in here (like the Title)
- \<body>: all content is in here
- \<span>: makes them only take as much space as they need, unlike div which makes the content inside take the whole line.
- \<h1>, \<h2>, \<h3> … \<h6> : size of headings, just like in a README file
- \<p> : paragraph tag
- \<img> : lets you embed images
- \<a> : hyperlink tag 
Usage: \<a href = "https://google.com" target ="_blank"> Go to Google</a>
target =”_blank” → opens in new page
- \<b> , <i> : bold and italic
- \<button onclick=""> : ugly default button
- \<input id="" type = ""> : takes in input

Final Result:

Actual Landing Page of Zerodha:
<img width="1440" alt="Screenshot 2023-12-01 at 5 35 28 PM" src="https://github.com/KAUSSHIK/ZerodhaClone/assets/32772050/35ef8036-bbd4-4521-a7b5-579ae77dd0ee">


My Cloned Landing Page:
<img width="1440" alt="Screenshot 2023-12-01 at 5 35 12 PM" src="https://github.com/KAUSSHIK/ZerodhaClone/assets/32772050/77d5e379-f642-46b8-b7fb-6c22be111b6e">


