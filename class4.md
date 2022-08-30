# **Notes for class 4**

	*Class 4 Notes*
	
 What is a wireframe?
Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. This process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team.

It’s likely to be to your advantage to start off hand-drawing your wireframes before executing more detailed versions using an online app or software. The following wireframes should give you a good idea of how information can be organized on the screen.

Here are a number of ways different designers can structure the process from design to implementation:
* Wireframe > Interactive Prototype > Visual > Design
* Sketch > Code
* Sketch > Wireframe > Hi-Def Wireframe > Visual > Cod
* Sketch > Wireframe > Visual > Code

Make sure you have your user flow mapped out

1. Clarity

2. Confidence

3. Simplicity is key

## **HTML**

HTML is a markup language that defines the structure of your content. 

Here, we have the following:

<!DOCTYPE html> — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
<html></html> — the <html> element. This element wraps all the content on the entire page and is sometimes known as the root element. It also includes the lang attribute, setting the primary language of the document.
<head></head> — the <head> element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
<meta charset="utf-8"> — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
<meta name="viewport" content="width=device-width"> — This viewport element ensures the page renders at the width of viewport, preventing mobile browsers from rendering pages wider than the viewport and then shrinking them down.
<title></title> — the <title> element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
<body></body> — the <body> element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.
Images
Let's turn our attention to the <img> element again:

<img src="images/firefox-icon.png" alt="My test image">
Copy to Clipboard
As we said before, it embeds an image into our page in the position it appears. It does this via the src (source) attribute, which contains the path to our image file.

We have also included an alt (alternative) attribute. In the alt attribute, you specify descriptive text for users who cannot see the image, possibly because of the following reasons:

They are visually impaired. Users with significant visual impairments often use tools called screen readers to read out the alt text to them.
Something has gone wrong causing the image not to display. For example, try deliberately changing the path inside your src attribute to make it incorrect. If you save and reload the page, you should see something like this in place of the image:



Links are very important — they are what makes the web a web! To add a link, we need to use a simple element — <a> — "a" being the short form for "anchor". To make text within your paragraph into a link, follow these steps:

Choose some text. We chose the text "Mozilla Manifesto".
Wrap the text in an <a> element, as shown below:
<a>Mozilla Manifesto</a>
Copy to Clipboard
Give the <a> element an href attribute, as shown below:
<a href="">Mozilla Manifesto</a>
Copy to Clipboard
Fill in the value of this attribute with the web address that you want the link to:
<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>
Copy to Clipboard
You might get unexpected results if you omit the https:// or http:// part, called the protocol, at the beginning of the web address. After making a link, click it to make sure it is sending you where you wanted it to.

### **SEMANTICS**

Semantics in JavaScript
In JavaScript, consider a function that takes a string parameter, and returns an <li> element with that string as its textContent. Would you need to look at the code to understand what the function did if it was called build('Peach'), or createLiWithContent('Peach')?

Semantics in CSS
In CSS, consider styling a list with li elements representing different types of fruits. Would you know what part of the DOM is being selected with div > ul > li, or .fruits__item?

Semantics in HTML
In HTML, for example, the <h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

Some of the benefits from writing semantic markup are as follows:

Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
Screen readers can use it as a signpost to help visually impaired users navigate a page
Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
Suggests to the developer the type of data that will be populated
Semantic naming mirrors proper custom element/component naming



[Back to Home](https://stevenrej.github.io/reading-notes/)
