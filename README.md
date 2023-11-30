# Complete-HTML
This is repository in which we are going to learn complete HTML language from beginner to advance.<br> 
we are going to complete HTML in 9 lessons.
<h2>Lesson 1 : Introduction to HTML </h2>
<ul> <h3><strong>HTML</strong> Stands for Hyper Text Markup Language</h3>
<li>HTML is the standard markup language for creating web pages</li>
<li>HTML describes the the structure of web pages and it consists of a series of elements </li>
</ul>
<h3>HTML Element</h3>
  <p> An HTML element is defined by a start tag, some content, and an end tag:<br>
&lt;tagname> Content goes here...&lt;/tagname><br>
The HTML element is everything from the start tag to the end tag.<br>
  Reference of <a href="https://www.w3schools.com/tags/"> Elementes or tag</a></p>
<h3>HTML attributes</h3>
<p>html attributes provides some special power to the element <br> Reference : <a href="https://www.w3schools.com/html/html_attributes.asp">HTML attributes</a></p>

<h2>Lesson 2 : HTML head tag</h2>
<p>The &lt;head> element is a container for metadata (data about data) and is placed between the <html> tag and the &lt;body> tag.<br>
Metadata is data about the HTML document. Metadata is not displayed.<br>
Metadata typically define the document title, character set, styles, scripts, and other meta information.
The following elements can go inside the &lt;head> element:<br>
  <ul>
<li>&lt;title> (required in every HTML document)</li>
<li>&lt;style></li>
<li>&lt;base></li>
<li>&lt;link></li>
<li>&lt;meta></li>
<li>&lt;script></li>
<li>&lt;noscript></li>
  </ul>
</p>
  
<h2>Lesson 3 : Text Formatting</h2>
<h3> HEADING TAGS </h3>
<p>HTML headings are defined with the &lt;h1> to &lt;h6> tags.<br>
&lt;h1> defines the most important heading. &lt;h6> defines the least important heading.</p>
<h3>Paragraph tag</h3>
<p>The HTML &lt;p> element defines a paragraph.<br>
A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.</p>
<h3>Suberscript</h3>
<p>The &lt;sub> tag in HTML is used to define subscript text. Subscript text appears half a character below the normal line, and is sometimes used for chemical formulas, like H&lt;sub>2&lt;/sub>O(H<sub>2</sub>O)</p>
<h3>Superscript</h3>
<p>The &lt;sup> tag in HTML is used to define superscript text. Superscript text appears half a character above the normal line, and is sometimes used for footnotes, like 3&lt;sup>2&lt;/sup>  (3<sup>2</sup> ) </p>
<p> references : <a href ="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">TEXT FORMATING</a></p>

<h2>Lesson 4 : Images & Responsive Images</h2>
<p>The HTML &lt;img> tag is used to embed an image in a web page.<br>
Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.<br><br> &lt;img src="image.jpg" alt="this is alternate text" width="500px" hight="600px"&gt;<br><br> <b>src :</b>specifies the path to the image<br><b>alt:</b>specifies an alternate text for an image.<br> <b>Width</b> and <b>height</b> specifies the width and height of an image respectivly. </p>
<h3> Responsive Images </h3>
<p> We should use Responsive images for two scenarious:<br>1. Fetch lower quality images on low resolution screens to load images faster.<br>2. To tackle the Art Direction problem.(simply it is showing image larger in big screens and smaller (zoom) in small screen)</p>

<h2>Lesson 5 : Lists</h2>
<h3>Unordered List</h3>
</p> The &lt;ul> HTML element represents an unordered list of items, typically rendered as a bulleted list. </p>
&lt;ul><br>&lt;li>Apple&lt;/li><br>&lt;li>Banana&lt;/li><br>&lt;li>Graphs&lt;/li><br>&lt;/ul><br>
<ul><li>Apple</li><li>Banana</li><li>Graphs</li></ul>

<h3> Ordered List</h3>
<p> the &lt;ol> HTML element represents an ordered list of item- typically rendered as a numbered list</p>
&lt;ol type="1"><br>&lt;li>Coffee&lt;/li><br>&lt;li>Tea&lt;/li><br>&lt;/ol><br>
<ol type="1"><li>Coffee</li><li>Tea</li></ol>
<table>
  <th>Type</th>
  <th>Description</th>
  <tr><td>type="1"</td>
  <td>The list items will be numbered with numbers (default)</td></tr>
  <tr>
<td>type="A"</td>
<td>The list items will be numbered with uppercase letters</td>
</tr>
  <tr>
<td>type="a"</td>
<td>The list items will be numbered with lowercase letters</td>
</tr>
  <tr>
<td>type="I"</td>
<td>The list items will be numbered with uppercase roman numbers</td>
</tr>
  <tr>
<td>type="i"</td>
<td>The list items will be numbered with lowercase roman numbers</td>
</tr>
</table>

<h2>Lesson 6 : Tabbles</h2> 
<p>HTML tables allow web devlopers to arrange data into rows and colums</p>
<p>table is created through &lt;table> tag.</p>
<h3>Table Cells</h3>
<p>Each table cell is defined by &lt;td> and a &lt;/td> tag.<br> td stands for table data<br> Everithing between this tag is content of table cell</p>
<h3>Table Rows</h3>
<p>Each table row starts with a &li;tr> and ends with a &li;/tr> tag. <br> tr stands for table row</p>
<h3> Table Headers</h3>
<p>Sometimes you want your cells to be table header cells. In those cases use the &lt;th> tag instead of the &lt;td> tag:<br>
th stands for table header.</p>

<table>
  <tr>
    <th>Tag</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_table.asp">&lt;table></a></td>
    <td>Defines a table</td>
  </tr>
   <tr>
    <td><a href="https://www.w3schools.com/tags/tag_th.asp">&lt;th></a></td>
    <td>Defines a header cell in a table</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_tr.asp">&lt;td></a></td>
    <td>Defines a header row in a table</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_td.asp">&lt;td></a></td>
    <td>Defines a cell in a tablee</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_caption.asp">&lt;caption></a></td>
    <td>Defines a table caption</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_colgroup.asp">&lt;colgroup></a></td>
    <td>Specifies a group of one or more columns in a table for formatting</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_col.asp">&lt;col></a></td>
    <td>Specifies column properties for each column within a &lt;colgroup> element</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_thead.asp">&lt;thead></a></td>
    <td>Groups the header content in a table</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_tbody.asp">&lt;tbody></a></td>
    <td>Groups the body content in a table</td>
  </tr>
  <tr>
    <td><a href="https://www.w3schools.com/tags/tag_tfoot.asp">&lt;tfoot></a></td>
    <td>Groups the footer content in a table</td>
  </tr>
</table>

<h2>Lesson 7 : Links in HTML</h2>

<h3> Hyper text in HTML</h3>
<p>"Hypertext" refers to links that connect web pages to one to another, either within a single website or between websites.</p>

<h3> The Anchor tag</h3>
<p> the &lt; HTML element(or anchor element) with its href attribute, creates a hyperlink to web pages,files,email,addresses,locations in the same page, or anything else a URL can address.<br><br> &lt;a href="www.google.com ">click&lt;/a><br>&lt;a target="_blank" href="www.google.com ">click&lt;/a> it will open this URL in new window</p>

<h3>The href attribute</h3>
<p>The URL that the hyperlink points to.<br>Links are not restricted to HTTP-based URLs- they can use any URL scheme supported by browsres:<br><li>telephone numbers with tel: URLs</li><li>Email address with malito: URLs</li></p>

<h2>Lesson 8 : Forms & Input tags</h2>
<p> An HTML form is used to collect user input.The user input is most often sent to a server for processing.</p>
<h3>The HTML &lt;form> </h3> <p> it is used to create an HTML from for user input also form element is a container for differnet types of inputs.</p>
<h3>Text Fileds</h3>
<p>The &lt;input type="text"> defines a single-line input field for text input.</p>
<h3>The &lt;label> Element</h3>
<p>
The &lt;label> tag defines a label for form elements.<br>

The &lt;label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focuses on the input element.<br>

The &lt;label> element also helps users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the &lt;label> element, it toggles the radio button/checkbox.<br>

The for attribute of the &lt;label> tag should be equal to the id attribute of the <input> element to bind them together.</p>
<p>reference : <a href="https://www.w3schools.com/html/html_forms.asp">HTML Forms</a></p>

<h2>Lesson 9 : Semantic tags</h2>
<h3>Most commonly used semantic tags</h3>
<ul>
<li>header</li>
<li>main</li>
<li>nav</li>
<li>section</li>
<li>article</li>
<li>aside</li>
<li>footer</li>
</ul>
