# Learning HTML

## [HTML Cheatsheet](https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf)

MDN has a category of "permitted content" which is what is allowed for that specific element.

### `<!DOCTYPE html>`
  - This lets our browser know we're using HTML5. Now our browswer knows we're using the latest features in HTML

### `<html></html>`
  - Permitted content is one head and one body element.

### `<head></head>`
  - Document meta data
  - Information about your webpage, like scripts, stylesheets

### `<title></title>`
  - The title element is going to change what we see in the tab on google
  - google looks for this element in the head.
  - if not there, google will default to the file name

### `<ol> Ordered list`
  <li> list item with numbers

### `<ul> Unordered list`
  <li> list item bullet points

### `<a></a>`
  - Anchor elements
  - One of the most important elements in HTML
  - They are inline

## Attributes
  - Pieces of info we can pass into a tag
  - ref, href, id, class, etc...

### `<img>`
  - Doesn't have a closing tag
  - I makes sense because we only provide a url/location and we don't have text inside that image.
  - Doen't have text
  - src=""
  - **alt="I am a baby chick"** To create a description of what the img is


# Learning what HTML5 actually is

  - The latest evolution of the standard that defines HTML.
  - Refers to a larger set of technologies
  - [HTML Living Standard](https://html.spec.whatwg.org) - Document that explains how html should work. Mainly for browswers to understand how to implement html.

# Inline vs. Block Elements
 - `<h1> & <p>` tags are examples of a block level element
  - If you inspect and hover over the element, you can see if it is inline or block
 - `<a>` is an example of an inline element
 - `<div>` The Content Division Element - official description
  - A generic element to contain or group elements
  - Block level
  - `<span>` is a generic inline container for phrasing content, which doesn't inherntly represent anything.
  - Also used to group element.

# Odd Assortment of Elements: hr, br, sup & sub
  - These tags do not have closing tags
  - `<hr>` Element that represents a thematic break between paragraph-level elements
  - `<br>` Makes a break in your content
  - These do have closing tags
  - `<sup>` The Superscript element specifies inline text which is to be displayed as superscript a<sup>2</sup> + b<sup>2</sup> = c<sup>2</sup>
  - `<sub>` The Supscript element specifies inline text which is to be displayed as a subscript eg: H<sub>2</sub>O

# HTML Entities
  - Special code/sequences that we can use inside our HTML that result in different characters
  - eg: copywrite symbols,
  - Start with an ampersand and end with semicolon
  - Used to display reserved characters, that normally would be invalid
  - Also used in place of difficult type characters

# Semantic Markup - Relating to meaning
  - ### Adds meaning to markup, making your code more crawlable/accessible
  - `<footer>`, `<header>`, `<section>`, `<nav>`, `<details>`, etc..
  - A web crawler, or spider, is a type of bot that is typically operated by search engines like Google and Bing. Their purpose is to index the content of websites all across the Internet so that those websites can appear in search engine results.
  - `<section>` - Represents a standalone section--which doesn't have a more specific semantic element to represent it--contained within an HTML document.
  - `<article>` represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). Examples include: a forum post, a magazine or newspaper article, or a blog entry, a product card, a user-submitted comment, an interactive widget or gadget, or any other independent item of content.
  - The `<aside>` HTML element represents a portion of a document whose content is only indirectly related to the document's main content. Asides are frequently presented as sidebars or call-out boxes.

# Emmet
## [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)
  - Helps us write HTML markup
  - Uses special syntax