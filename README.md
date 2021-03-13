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
## Creates headlines -- H1=largest, H6=smallest
```<h1> </h1> --> <h6> </h6>```
## Creates bold text (should use <strong> instead)
```<b> </b>```
## Creates italicized text (should use <em> instead)
```<i> </i>```
## Creates typewriter-style text
```<tt> </tt>```
## Used to define source code, usually monospace
```<code> </code>```
## Creates a citation, usually processed in italics
```<cite> </cite>```
## Creates address section, usually processed in italics
<address> </address>
<em> </em>
Emphasizes a word (usually processed in italics)
<strong> </strong>
Emphasizes a word (usually processed in bold)
<font size=?> </font>
Sets size of font - 1 to 7 (should use CSS instead)
<font color=?> </font>
Sets font color (should use CSS instead)
<font face=?> </font>
Defines the font used (should use CSS instead)
Links
<a href="URL">clickable text</a>
Creates a hyperlink to a Uniform Resource Locator
<a href="mailto:EMAIL_ADDRESS">clickable text</a>
Creates a hyperlink to an email address
<a name="NAME">
Creates a target location within a document
<a href="#NAME">clickable text</a>
Creates a link to that target location
Formatting
<p> </p>
Creates a new paragraph
<br>
AInserts a line break (carriage return)
<blockquote> </blockquote>
Puts content in a quote - indents text from both sides
<div> </div>
Used to format block content with CSS
<span> </span>
Used to format inline content with CSS
Lists
<ul> </ul>
Creates an unordered list
<ol start=?> </ol>
Creates an ordered list (start=xx,
where xx is a counting number)
<li> </li>
Encompasses each list item
<dl> </dl>
Creates a definition list
<dt>
 Precedes eachdefintion term
<dd>
 Precedes eachdefintion
 Graphical elements
<hr>
Inserts a horizontal rule
<hr size=?>
Sets size (height) of horizontal rule
<hr width=?>
Sets width of rule (as a % or absolute pixel length)
<hr noshade>
Creates a horizontal rule without a shadow
<img src="URL" />
Adds image; it is a separate file located at the URL
<img src="URL" align=?>
Aligns image left/right/center/bottom/top/middle (use CSS)
<img src="URL" border=?>
Sets size of border surrounding image (use CSS)
<img src="URL" height=?>
Sets height of image, in pixels
<img src="URL" width=?>
Sets width of image, in pixels
<img src="URL" alt=?>
Sets the alternate text for browsers that can't
process images (required by the ADA)
 HTML Cheatsheet page 2 of 2
Forms
<form> </form>
Defines a form
<select multiple name=? size=?> </select>
Creates a scrolling menu. Size sets the number of
menu items visible before user needs to scroll.
<select name=?> </select>
Creates a pulldown menu
<option>
Sets off each menu item
<textarea name=? cols="x" rows="y"></textarea>
Creates a text box area. Columns set the width;
rows set the height.
<input type="checkbox" name=? value=?>
Creates a checkbox.
<input type="checkbox" name=? value=? checked>
Creates a checkbox which is pre-checked.
<input type="radio" name=? value=?>
Creates a radio button.
<input type="radio" name=? value=? checked>
Creates a radio button which is pre-checked.
<input type="text" name=? size=?>
Creates a one-line text area. Size sets length, in
characters.
<input type="submit" value=?>
Creates a submit button. Value sets the text in the
submit button.
<input type="image" name=? src=? border=? alt=?>
Creates a submit button using an image.
<input type="reset">
Creates a reset button
Tables (use only for data layout - use CSS for page layout) Table attributes (only use for email newsletters)
<table> </table>
Creates a table
<tr> </tr>
Sets off each row in a table
<td> </td>
Sets off each cell in a row
<th> </th>
Sets off the table header (a normal cell with bold,
centered text)
<table border=?>
Sets the width of the border around table cells
<table cellspacing=?>
Sets amount of space between table cells
<table cellpadding=?>
Sets amount of space between a cell's border and
its contents
<table width=?>
Sets width of the table in pixels or as a percentage
<tr align=?>
Sets alignment for cells within the row
(left/center/right)
<td align=?>
Sets alignment for cells (left/center/right)
<tr valign=?>
Sets vertical alignment for cells within the row
(top/middle/bottom)
<td valign=?>
Sets vertical alignment for cell (top/middle/bottom)
<td rowspan=?>
Sets number of rows a cell should span (default=1)
<td colspan=?>
Sets number of columns a cell should span
<td nowrap>
Prevents lines within a cell from being broken to fit
HTML5 input tag attributes
(not all browsers support; visit http://caniuse.com
 for details)
<input type="email" name=?>
 Sets a single-line textbox for email addresses
<input type="url" name=?>
 Sets a single-line textbox for URLs
<input type="number" name=?>
 Sets a single-line textbox for a number
<input type="range" name=?>
 Sets a single-line text box for a range of numbers
<input type="date/month/week/time" name=?>
 Sets a single-line text box with a calendar
 showing the date/month/week/time
<input type="search" name=?>
 Sets a single-line text box for searching
<input type="color" name=?>
 Sets a single-line text box for picking a color 
