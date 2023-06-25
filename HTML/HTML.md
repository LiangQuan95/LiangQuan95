# HTML

When creating new file, your **homepage** will need to be name as **index.html**

In the file, you will need to declare &lt;!doctype html&gt; //  &lt;!doctype html&gt; declaration lets the web browser treats your document as a html5 document.

**tags**, it is usually comes in pair, opening and closing. &lt;html&gt; opening tag. &lt;/html&gt; closing tag

Visual studio code
when running live server, you can set the perfence of which web browser to open. File - Preferences - Settings - Extensions - Live Server Config - Custom browser

# Tags syntax
&lt;html&gt;&lt;/html&gt;<br>
&lt;head&gt;&lt;/head&gt;<br>
&lt;title&gt;&lt;/title&gt; // &lt;title&gt;Content&lt;/title&gt; tag with the content inbetween is called a title element. tags are part of an element.<br>
&lt;body&gt;&lt;/body&gt;<br>
&lt;h1&gt;&lt;/h1&gt; // h1-h6 is the header size, h1 being the largest<br>
&lt;hr&gt; // horizontal rule, add a header line<br>
&lt;br&gt; // line break<br>
&lt;form&gt;&lt;/form&gt; // create form to allow user to input data<br>
&lt;table&gt; &lt;tr&gt;&lt;th&gt;&lt;td&gt; // &lt;tr&gt; defines a row, &lt;th&gt; defines a table header cell, and &lt;td&gt; defines a table data cell.<br>
&lt;p&gt;&lt;/p&gt; // use lorem to make sample parapgrahs

&lt;!--This command is for comments--&gt;

# Creating hyperlink
&lt;a href="url link" target=_blank title= &gt;<br>
google<br>
&lt;/a&gt;

You can use **href** to reference to the other html file you created or use mailto:emailaddress to send email.

# Inserting image
place your image in the same folder as your html file
&lt;img src="image.png"&gt; <br>
For housekeeping, place your images into a common image folder within the html folder. <br>
Precede your src, &lt;src="/filename/image.png"&gt; <br>

# Inserting audio and video
&lt;audio controls autoplay muted loop src="filename.mp3"&gt;

if want to have backup, remove src in main line. put source tag, &lt;source src=""&gt;.<br> close tag &lt;/audio&gt;<br>
for video, replace audio tag to video tag

# Unordered and ordered list
&lt;ul&gt; OR &lt;ol type&gt;<br>
&lt;li&gt;&lt;/li&gt;<br>
&lt;/ul&gt; OR &lt;/ol&gt;<br>

# Description list 
dt dd, terms and definition

# Table 
use table, tr, th, td tags. Adjust using bgcolor align width

# Colors
Modify body, header(h1-h6) tags. style="", the background or text color can be written as the color itself, rgb, hexdecimal.

# Span & Div
Span = adds markup to text or portion of a document
Div = defines a division of a document

# Metatags
Add metatags to head tags.
Use &lt;meta name="viewport" content="width=device-width, initial-scale=1.0"&gt; This will scale your webpage to the mobile device screen width

# iframe
embed content from another source into an HTML document. e.g advertisement<br>
&lt;iframe src="embed website url OR another html file"&gt; 
remove border, style="border:0"

# button
onClick="", give function to the button <br>
id="", give id to a word
use script tags and function method(){document.getEelementById("id name").innerHTML=""}

# form
form, label, input tags.<br>
For form tag, use action, method. Two common method, GET & POST. GET is insecure (append data to end of the url), useful for search boxes.

For label tags, use for="xyz" <!--**for and id**, put same. This allows the user to easily navigate to the textbox and type in the details.
 
For input tag, format looks like &ltinput type="" id="xyz" name="variablename" placeholder="" required&gt; <br>
there is type="text"/"password"/"email"/"reset"/"submit"/"tel"/"date"/"number"/"checkbox"<br>
input type="radio" allow user to click button and select an option, eg. mr/mrs/ms/dr.<br>
To set only one option within same group, **name="title"** same for the rest of the input.

Use select tags for drop down list. Then use option tags










