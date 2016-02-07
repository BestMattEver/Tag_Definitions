## Basic Structure of an HTML Tag
HTML is composed of written phrases called 'tags'. Tags can be read by internet browsers and converted into webpages. Tags usually come in pairs: an opening tag, and a closing tag. Opening tags are started by using the less than character (<) then the name of the tag and any attributes it requires then a greater than character (>). A complete opening tag looks like this"

`<body>`

next, comes all the webpage content you want inside that tag.

`<body> This is a basic webpage`

and finally, a closing tag is required to tell the browser when to stop structuring the webpage using the tag. A closing tag is written using a less than character (<) then a backslash, then the name of the tag again, and finally a greater than character. A closing tag looks like this:

`</body>`

so, a fully realized pair of html tags would look like this:

`<body> this is a basic webpage </html>`


### `<html>`

the main enchilada, the whole `document`, that which wraps all the others... except for [`<!DOCTYPE>`](#doctype), for some reason.

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`

### `<!DOCTYPE>`

This is required to be put at the top of your HTML document. It tells the browser that what follows will be an html document, and not a pdf for instance.

* _parents_: none. it occurs before the HTML tag.
* _content_: Doctype has no content, only attributes such as 'HTML'.
* _display_: none


###`<!-- -->`

This is a comment tag. the browser will skip this tag altogether. whatever you put in this tag is only for humans to read.

* _parents_: none. it is allowed anywhere since browsers ignore it.
* _content_: text only
* _display_: none

###`<head>`

the head tag is not visible to users. Its function is to house various meta data about your site and link external files, like stylesheets and fonts.

* _parents_: <html> only
* _content_: flow content
* _display_: none


###`<body>`

This tag is used to denote the body of the HTML page. Inside it is where you must put all the content that a user will see on your webpage.

* _parents_: <html> only
* _content_: any flow content
* _display_: block

###`<div>`

A generic page division that should only be used if no other, more semantic choice is appropriate.

* _parents_: anything that accepts flow content
* _content_:  also all flow content
* _display_: `block`

###`<span>`

Span is similar to a div except that it is an inline element.

* _parents_: anything that accepts flow content
* _content_: also all flow content
* _display_: `inline`

###`<h1>`

this is a tag used for formatting titles. by default, it has a lot of text formatting attributes like making the size of the text larger and more bold.

* _parents_: anything that accepts flow content
* _content_: any flow content (usually just text?)
* _display_: block

###`<strong>`

This tag makes text bold. Any text content inside this tag is made bold.

* _parents_: Any element that accepts prhasing content or flow content
* _content_: Flow Content, Phrasing Content
* _display_: inline

###`<header>`

The header tag is a semantic tag used to denote the header of the page or section. It has no formatting of its own.

* _parents_: Any element that accepts Flow content.
* _content_: any flow content
* _display_: not sure...

###`<section>`

section is a semantic tag that has no formatting of its own. It is used to logically organize an html document into relevant... you guessed it... 'sections'.

* _parents_: Any element that accepts flow content. Note that a <section> element must not be a descendant of an <address> element.
* _content_: Any Flow Content [1]
* _display_: not sure...



. . .

###### Footnotes

[1](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Flow_content)
