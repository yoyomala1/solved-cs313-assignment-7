Download Link: https://assignmentchef.com/product/solved-cs313-assignment-7
<br>
<span class="kksr-muted">Rate this product</span>

We have already shared the java j2ee setup handout with one servlet and html file..Do the setup,if not already done.Execute the StudentServlet file and index.html given with the handout.

1. Design a new html page to take advisor id as input. Write a servlet to display the department to which the advisor belongs using java j2ee program.Output should contain advisor id and department name.

You can refer to some of the following instructions :

<ol>

 <li>Place the servlet mapping code in web.xml.Example :Here ServletName is the name of your servlet file.This following code snippet should be placed within &lt;web-app&gt;&lt;/web-app&gt; tags in the web.xml.&lt;servlet&gt; &lt;servlet-name&gt;ServletName&lt;/servlet-name&gt; &lt;servlet-class&gt;ServletName&lt;/servlet-class&gt; &lt;/servlet&gt;&lt;servlet-mapping&gt; &lt;servlet-name&gt;ServletName&lt;/servlet-name&gt; &lt;url-pattern&gt;/ServletName&lt;/url-pattern&gt; &lt;/servlet-mapping&gt;</li>

 <li>You can create your own html page for reading advisor id as input.But put the name of your servlet file correctly inside the form element.Example :&lt;form action=”ServletName”&gt;</li>