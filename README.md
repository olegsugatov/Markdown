# Markdown

Headers
-------

#H1
##H2
###H3
####H4
#####H5
######H6


Heading with underline
----------------------
Heading
=======

Heading
-------



Emphasis
--------
italic - *astrics* or _underscores_

bold   - **astrics** or __underscores__

italic+bold - **astrics or _underscores_**

strikethrought - ~~tildes~~



Links
-----

[inline-style link](http://www.github.com)

[inline-style link with title](http://www.github.com "Github's Homepage")

[reference-style link][Arbitrary case-insensitive reference text]

[relatively refecence-style to repository file](../blob/master/LICENSE)

[numbers for reference-style links][1]

Emoty text with linki [link]

URLs and URLs with angle brakets automaticaly beeing a link.
http://www.github.com or <http://www.github.com> and something example (but not on github)


[arbitrary case-insensitie reference text]: https://www.github.com
[1]: http://www.github.com
[link]: http://www.github.com



Lists
-----

1. First list item
2. Another item
⋅⋅* Unordered sub-list
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses



Images
------
inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

reference-style:
![alt-text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"



Code and Syntax Highlight
-------------------------
Inline `code` has `back-ticks around` it

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```


Tables
------

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3



Blockquotes
-----------

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

 

Inline HTML
-----------

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>


Horizontal Rule
---------------
Three or more...

---

Hyphens

***

Asterisks

___

Underscores


Link Breaks
-----------

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.


YouTube Embed
-------------

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/gGNid6IFg0U/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/gGNid6IFg0U/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
