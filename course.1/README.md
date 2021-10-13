## Course 1

Let us begin our first course by taking a look into how web browsers and the Internet in general work, then creating our
first website from scratch. We will view and utilize the most commonly used element tags in HTML5, with exercises
interweaved to test and confirm our understanding of certain tags.

### Web Browsers and the Internet

When thinking of the web, we imagine our computers talking with black-boxes, often called servers, that are told what to
show on our monitors. However, it's actually your computer doing much of the work. In fact, the only thing that these
servers do to your computer is feed you files and some pieces of data. Web browsers end up doing a lot of the heavy
lifting, with some capable of doing more than other browsers, or sometimes better in general.

### Tags of Importance

* `<!DOCTYPE html>` -
  * defines the type of document the browser is reading, in particular HTML5
  * all HTML files begin with this line to inform the web browser that it is reading an HTML file
* `<html></>` -
  * root of an HTML document
  * composed by a `HEAD` and `BODY` segment
* `<head></>` -
  * section of the doc that defines metadata info
  * some of this info includes the tab title, author, language encoding, and linking to other CSS files
* `<title></>` -
  * title rendered in the tab
* `<body></>` -
  * section of the doc that defines what is rendered
* `<h[1-6]></>` -
  * titles/headers, with the lower numbers being larger
  * we can use these with links to create a Table of Index or Contents table
* `<p></>` -
  * renders a paragraph (text)
  * it renders additional spacing before and after the tag
* `<b></>` -
  * bolding text
  * like other text style tags, this does not need to be inside a `p` tag
* `<br>` -
  * creates a spacing break
  * newlines and extra spaces in a paragraph tag are not rendered, so we use this to force a new line
* `<img>` -
  * images
* `<video></>` -
  * `<source></>` are used to defined multiple sources of the video
  * videos with multiple sources
* `<!-- -->` -
  * comments, ignored by the web browser but useful for the coder
* `<ol></>` and `<ul></>` -
  * ordered and unordered lists
  * `<li></>` creates a list item for either type of list
* `<a></>` -
  * anchor (link) that allows us to link to other documents or locations within the same document

### References

No programmer ever works without references, and web developers are no exceptions. For that,
[W3 Schools](https://www.w3schools.com/tags/default.asp) provides a great list of all tags under HTML5 with both a
description and examples that can be run on your web browser.
