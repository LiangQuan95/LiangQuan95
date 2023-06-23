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
&lt;/ul&gt; OR &lt;/ol type&gt;<br>

**description list** dt dd, terms and definition








