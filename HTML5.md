## Using HTML5

The old html used <div> to divide up sections on a page.  Now you can name the sections within the <div> to divide them up.

- '<nav>' - navigation element
- '<header>' - header element
- '<footer>' - footer element
- '<article>'
- '<aside>'
- '<section>'
- '<hgroup>' - heading group
- '<figure>'
- '<fig caption>'
- '<div>'

Extra Markup

The different versions of HTML had different versions of !DOCTYPE that helped identify the version it was in.
- html 5 = !DOCTYPE html
- html 4 =!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd"
- Transitional XHTML 1.0 = !DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/  xhtml1-transitional.dtd"
- Strict XHTML 1.0 = !DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/  xhtml1-strict.dtd"
- XML Declaration = ?xml version="1.0" ?

- '<!-- -->' = to add a comment that won't show up on page
- '<p id="pullquote">' = It is used to uniquely identify that element from other elements on the page. 
    - Its value should start with a letter or an underscore (not a number or any other character). 
    - It is important that no two elements on the same page have the same value for their id attributes (otherwise the value is no longer unique).
- '<p class="important">' = Sometimes, rather than uniquely identifying one element within a document, you will want a way to identify several elements as being different from the other elements on the page

- Block elements = Examples of block elements are <h1>, <p>, <ul>, and <li>
- Inline elements = Examples of inline elements are <a>, <b>, <em>, and <img>
