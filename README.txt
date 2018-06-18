FUNCTIONAL FEATURES
-------------------
The HTML files are used to describe a web page content. These are annotated by tags.
The HTML tags are of two types: element tags and void tags.
--> Element tags consists of three parts - start tag, content, end tag
--> Void tags consists only of the start tag.
The HTML tags are nested for better structure formation and understanding and these
indented can be called as the children.
The depth of a void tag or an element is the number of elements that surround it.
An element or void tag is a child of another element, if it is contained in that element
and is of depth one greater than the element as per the given requirement.
The project outputs the ArrayList of Strings with the name of the HTML tag and the 
number of children it encloses.

INPUT FORMAT
------------
<!DOCTYPE html>
<html>
<body>
<h1>My First Heading</h1>
<p>My first paragraph.
<hr>
Another ruler...
<hr>
No more rulers
</p>
<br>
<!-- I should be ignored -->
<p>Bold Example: <b> bold </b></p>
</body>
</html>

OUTPUT FORMAT
-------------
html 1
body 4
h1 0
p 2
hr
hr
br
p 1
b 0

NOTE:
-----
1. This Code was done as part of Assignment 3 in CS3 course(MACS, Dalhousie University)
2. HTMLSummarizerTest.java, Tester.java - Files rovided by Dr. Alexander Brodskey, Dalhousie University 
   for the purpose of testing.



