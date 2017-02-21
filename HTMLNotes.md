# HTML NOTES
## TAGS
HTML is a markup language composed by a set of elements that are the basis of its structure. These elements conform a toolbox authors can use to shape their documents.

An HTML element is usually composed by two tags: the opening tag and the closing tag. An opening tag consists of the element's name encolsed by the lesser-than "<" and greater-than ">" signs. The closing tag is constructed like the opening tag but, in this case, the element's name is preceded by a slash ("/").

The HTML tags follow an order such as the example bellow:

~~~
<HTML>
<HEAD>
<TITLE>Your Title Here</TITLE>
</HEAD>

<BODY>
<a> A Link Here </a>

<H1>This is a Header</H1>
<H2>This is a Medium Header</H2>

<P> This is a new paragraph!
<P> This is a new paragraph!</P> 

</BODY>
</HTML>
~~~

# TAG < a >
The HTML < a > element (or anchor element) creates a hyperlink to other web pages, files, locations within the same page, email addresses, or any other URL.

## Some Atributtes:
### _**href**_
Contains a URL or a URL fragment that the hyperlink points to.

### _**hreflang**_
This attribute indicates the human language of the linked resource. It is purely advisory, with no built-in functionality.

### _**referrerpolicy**_ 
Indicates which referrer to send when fetching the URL

### _**rel**_
Specifies the relationship of the target object to the link object. The value is a space-separated list of link types.

## Example

### Linking to an external location:
~~~
<a href="https://www.mozilla.com/">
External Link
</a>
~~~
### Linking to another section on the same page:
~~~~
<a href="#attr-href">
Description of Same-Page Links
</a>
~~~~
### Creating a clickable image

This small example use an image to link to the MDN home page. The home page will open in a new browsing context, that is a new page or a new tab.
~~~~
<a href="https://developer.mozilla.org/en-US/">
  <img src="https://mdn.mozillademos.org/files/6851/mdn_logo.png"/>
</a>
~~~~
You can find more information in:
link https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a link

<a href="https://developer.mozilla.org/en-US/" target="_blank">
  <img src="https://mdn.mozillademos.org/files/6851/mdn_logo.png"
       alt="MDN logo" />
</a>

# TAG < P >
The HTML < p > element represents a paragraph of text. Paragraphs are usually represented in visual media as blocks of text that are separated from adjacent blocks by vertical blank space and/or first-line indentation. Paragraphs are block-level elements.

## Some Atributtes:

_This element includes the global attributes._
## Example
~~~~
<p> This is the first paragraph of text.
    This is the first paragraph of text.
    This is the first paragraph of text.
    This is the first paragraph of text.
</p>
<p> This is the second paragraph.
    This is the second paragraph.
    This is the second paragraph.
    This is the second paragraph.
</p>
 ~~~~

