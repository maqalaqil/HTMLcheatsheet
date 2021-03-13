# HTMLcheatsheet
 
# Basic Tags

## Creates an HTML document
```<html> </html>```
## Sets off the title & other info that isn't displayed
```<head> </head>```
## Sets off the visible portion of the document

``` <body> </body> ```
## Puts name of the document in the title bar; when bookmarking pages, this is what is bookmarkedBody attributes (only used in email newsletters)
```<title> </title>```
## Sets background color, using name or hex value
```<body bgcolor=?>```
## Sets text color, using name or hex value
```<body text=?>```
## Sets color of links, using name or hex value
```<body link=?>```
## Sets color of visited links, using name or hex value
```<body vlink=?>```
## Sets color of active links (while mouse-clicking)
```<body alink=?>```
# Text Tags
## Creates preformatted text
```<pre> </pre>```
## Creates headlines H1=largest H6=smallest
```<h1></h1> --> <h6> </h6>```
## Creates bold text (should use instead)
```<b> </b>```
## Creates italicized text (should use em instead)
```<i> </i>```
## Creates typewriter-style text
```<tt> </tt>```
## Used to define source code, usually monospace
```<code> </code>```
## Creates a citation, usually processed in italics
```<cite> </cite>```
## Creates address section, usually processed in italics
```<address> </address>```
## Emphasizes a word (usually processed in italics)
```<em> </em>```
## Emphasizes a word (usually processed in bold)
```<strong> </strong>```
## Sets size of font - 1 to 7 (should use CSS instead)
```<font size=?> </font>```
## Sets font color (should use CSS instead)
```<font color=?> </font>```
## Defines the font used (should use CSS instead)
```<font face=?> </font>```
# Links
## Creates a hyperlink to a Uniform Resource Locator
```<a href="URL">clickable text</a>```
## Creates a hyperlink to an email address
```<a href="mailto:EMAIL_ADDRESS">clickable text</a>```
## Creates a target location within a document
```<a name="NAME">```
## Creates a link to that target location Formatting
```<a href="#NAME">clickable text</a>```
## Creates a new paragraph
```<p> </p>```
## AInserts a line break (carriage return)
```<br>```
## Puts content in a quote - indents text from both sides
```<blockquote> </blockquote>```
## Used to format block content with CSS
```<div> </div>```
## Used to format inline content with CSS
```<span> </span>```
# Lists
## Creates an unordered list
```<ul> </ul>```
## where xx is a counting number)
```<ol start=?> </ol>```
## Encompasses each list item
```<li> </li>```
## Creates a definition list
```<dl> </dl>```
## Precedes eachdefintion term
```<dt>```
## Graphical elements
```<dd>```
## Inserts a horizontal rule
```<hr>```
## Sets size (height) of horizontal rule
```<hr size=?>```
## Sets width of rule (as a % or absolute pixel length)
```<hr width=?>```
## Creates a horizontal rule without a shadow
```<hr noshade>```
## Adds image; it is a separate file located at the URL
```<img src="URL" />```
## Aligns image left/right/center/bottom/top/middle (use CSS)
```<img src="URL" align=?>```
## Sets size of border surrounding image (use CSS)
```<img src="URL" border=?>```
## Sets height of image, in pixels
```<img src="URL" height=?>```
## Sets width of image, in pixels
```<img src="URL" width=?>```
## Sets the alternate text for browsers that can't process images (required by the ADA)
```<img src="URL" alt=?>```

# Forms
## Defines a form
```<form> </form>```
## Creates a scrolling menu. Size sets the number of menu items visible before user needs to scroll.
```<select multiple name=? size=?> </select>```
## Creates a pulldown menu
```<select name=?> </select>```
## Sets off each menu item
```<option>```
## Creates a text box area. Columns set the width; rows set the height.
```<textarea name=? cols="x" rows="y"></textarea>```
## Creates a checkbox.
```<input type="checkbox" name=? value=?>```
## Creates a checkbox which is pre-checked.
```<input type="checkbox" name=? value=? checked>```
## Creates a radio button
```<input type="radio" name=? value=?>```
## Creates a radio button which is pre-checked.
```<input type="radio" name=? value=? checked>```
## Creates a one-line text area. Size sets length, in
characters.
```<input type="text" name=? size=?>```
## Creates a submit button. Value sets the text in the submit button.
```<input type="submit" value=?>```
## Creates a submit button using an image.
```<input type="image" name=? src=? border=? alt=?>```
## Creates a reset button
```<input type="reset">```

# Tables (use only for data layout - use CSS for page layout) Table attributes (only use for email newsletters)
## Creates a table
```<table> </table>```
## Sets off each row in a table
```<tr> </tr>```
## Sets off each cell in a row
```<td> </td>```
## Sets off the table header (a normal cell with bold,
centered text)
```<th> </th>```
## Sets the width of the border around table cells
```<table border=?>```
## Sets amount of space between table cells
```<table cellspacing=?>```
## Sets amount of space between a cell's border and
## its contents
```<table cellpadding=?>```
## Sets width of the table in pixels or as a percentage
```<table width=?>```
## Sets alignment for cells within the row (left/center/right)
```<tr align=?>```
## Sets alignment for cells (left/center/right)
```<td align=?>```
## Sets vertical alignment for cells within the row
(top/middle/bottom)
```<tr valign=?>```
## Sets vertical alignment for cell (top/middle/bottom)
```<td valign=?>```
## Sets number of rows a cell should span (default=1)
```<td rowspan=?>```
## Sets number of columns a cell should span
```<td colspan=?>```
## Prevents lines within a cell from being broken to fit HTML5 input tag attributes(not all browsers support; visit http://caniuse.com for details)
```<td nowrap>```
## Sets a single-line textbox for email addresses
```<input type="email" name=?>```
## Sets a single-line textbox for URLs
```<input type="url" name=?>```
## Sets a single-line textbox for a number
```<input type="number" name=?>```
## Sets a single-line text box for a range of numbers
```<input type="range" name=?>```
## Sets a single-line text box with a calendar showing the date/month/week/time
```<input type="date/month/week/time" name=?>```
## Sets a single-line text box for searching
```<input type="search" name=?>```
## Sets a single-line text box for picking a color 
```<input type="color" name=?>```
