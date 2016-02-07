## Basic Structure of an HTML Tag
HTML is composed of written phrases called 'tags'. Tags can be read by internet browsers and converted into webpages. Tags usually come in pairs: an opening tag, and a closing tag. Opening tags are started by using the less than character (<) then the name of the tag and any attributes it requires then a greater than character (>). A complete opening tag looks like this"

`<body>`

next, comes all the webpage content you want inside that tag.

`<body> This is a basic webpage`

and finally, a closing tag is required to tell the browser when to stop structuring the webpage using the tag. A closing tag is written using a less than character (<) then a backslash, then the name of the tag again, and finally a greater than character. A closing tag looks like this:

`</body>`

so, a fully realized pair of html tags would look like this:

`<body> this is a basic webpage </html>`

### Attributes

* `class` -- a space-separated list of category names
*

### `<html>`

the main enchilada, the whole `document`, that which wraps all the others... except for [`<!DOCTYPE>`](#doctype), for some reason.

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!

## `<!DOCTYPE>`

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!


##`< !-- -->`

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!


##`<head>`

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!


##`<body>`

* _parents_: none, it's the top
* _content_: _only_ [`<head>`](#head) and [`<body>`](#body)
* _display_: `block`, maybe? I mean, I can see it... RESEARCH!

## `<div>`

A generic page division that should only be used if no other, more semantic choice is appropriate.

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`

##`<span>`

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`

##`<h1>`

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`

##`<strong>`

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`

##`<header>`

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`

##`<section>`

* _parents_: anything that accepts [Flow Content][1], which is apparently a lot of things.
* _content_: any [Flow Contant][1], palpable content (WTF?)
* _display_: `block`



. . .

###### Footnotes

[1](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Flow_content)
