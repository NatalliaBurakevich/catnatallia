---
title: example
description: example
tags: [tutorial:product/sapHana, tutorial:product/hana_studio]
---

999 678 9999
Update file 5
update 12

You can use:

***Text*** (including bold, italic, etc)

  **Example:** 
It's very easy to make some words **bold** and other words *italic* and ***bold italic*** with Markdown.

***Headers***

  **Example:** 
## This is an h2 header 
### This is an h3 header
###### This is an h6 header

***Lists***

  **Example:** 
  
Sometimes you want numbered lists:

1. One
2. Two 
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two

***Blockquotes***

  **Example:** 
In the words of Abraham Lincoln:
> Pardon my French

***Links***

  **Example:** 
[Primer] [id]:
[id]: http://tut.by

<http://tut.by>

<address@example.com>

***There are three different types of messages: Note, Caution and Warning.***

>### Warning
>This is a Warning.

&nbsp;

>### Caution
>This is a Caution.

&nbsp;

>### Note

>This is a note.

&nbsp;

***Images*** (all images are stored on GitHub, URLs are rewritten to absolute)

Format: `![Alt Text](url)`

  **Example:** 
![Image](https://octodex.github.com/images/yaktocat.png)
![Example](http://www.kinomania.ru/images/posters/154766.jpg)


![Example](http://bestfotoposter.ru/downloads/priroda/more/6000%D1%854285-96dpi-foto-oblaka-nad-morem.jpg)


***Code blocks:***

```ruby
 quit;
 !@#$%^&*&*(*(()_++|"}?><>??*&^%#!~~~~@33123-090=|"]?>{}|\\
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  exit;
```

  **Example:** 
```javascript
quit;
function fancyAlert(arg) { function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) {function fancyAlert(arg) { 
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
function fancyAlert(arg) {
  if(arg) {
  20 line
  21 line
```
***Task Lists*** (Please note, this requires empty line before task list):

  **Example:** 
  
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

***Tables:***

  **Example:** 

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


and

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
