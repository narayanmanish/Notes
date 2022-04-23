HTML    Notes
============>

heading Tag in HTML
====================
>1)<h1>welcome</h1>
>1)<h2>welcome</h2>
>1)<h3>welcome</h3>
>1)<h4>welcome</h4>
>1)<h5>welcome</h5>
>1)<h6>welcome</h6>


Table Tage in HTML (v.imp)
======================
create table in html with the help of <table> tag
 <tr>   tag use for the Row 
 <th>  tag use for the colomn in heading format
 <td>  tag  also use for normal column

example
========
                          <table>
                               <tr>
                                 <th>Name</th>
		                 <th>Course</th>
		                 <th>Mobile</th>
                               </tr>  
		               <tr>
                                  <td>Vimal</td>
		                  <td>BCA</td>
		                 <td>958969699</td>
                               </tr>         
                         </table>

List tag in HTML
===============>
<ul>  tag use for unorder list
<ol>  tag use for order list
<li>   tag use for list must be inside <ul> or <ol>

example
=======>     unorder list
	     ------------------
	         <ul>
		<li>Apple<li>
		<li>Banana<li>
		<li>papaya<li>
                          </ul>
 
                    orderd list
	   ---------------                 
      	        <ol>
		<li>Apple<li>
		<li>Banana<li>
		<li>papaya<li>
                          </ol>
 
Hyperlink in HTML
================>
<a>      tag  use for the craete the hyperlink
 href=""  inside href you pass the location ,where you want to send 

example
========>
                      <a href="home.html">Home</a> 

Form tag in HTML  (v.imp)
=====================>
1.  create the form with the help of <form> tag
2.  without form we can not send the data

action="home.php"
=====>
  >  action is a attribute it define location (ye batyega kis file pe apka data jayega ); 

get()=>   
=======>
  1) In the case of get() method data show in url
  2) In the case of get() method we can not send binary data like(image,audio,video etc) 
  3) In the case of get () method we can send limted data

post()=>   
=======>
  1) In the case of post() method data hide from url
  2) In the case of post() method we can send binary data like(image,audio,video etc) 
  3) In the case of post () method we can send Unlimted data


<input type="text" name="username" id="userid">

<input type="text" name="user_father_name" id="user_father_id">

<input type="password" name="">

<input type="email">

<input type="radio">  // use for single selection

<input type="checkbox">  // use for multiple selection 

<input type="button"> 

<input type="submit"> 


Block And Inline Element or tag
==========================>

Block Element
---------------------->
1. Block element cover full width and cursor put new line.

  example--->   <div>,<h1>,<p> etc

Inline Element
---------------------->
1. Inline element cover width depend upon our content and cursor in same line.
2. In inline element we can not apply height , width,.
3. With the help of some property we can convert (inline to block,  block to inline) 
       through the css.
  
  property name:   >   display:inline;
                              >   display:inline-block;
                              >   display:block;

  example--->   <span>,<a>,<input> etc
  


CSS (Cascadding Style Sheet)
==========================>

What is Css 
------------------>    > With the help of css we can provide the beauty of HTML element
                               like (color , background, fontsize, border etc).


Cascadding
==========>    When we apply css multiple rule to a HTML element called cascadding
    
             exmple-> 
                         h1{
                            color:red;
                            background:pink;
                            font-size:100px;
                           }

Style
-------->      Style means provide color , border etc.

Sheet
--------->      Where you writes the code inside <html> tag  called the sheet.  

We have 3 way to apply css in HTML page
===================================>

1)  Internal Css 
    -------------------
       >  Internal css means write the css inside html page within <style> tag,
       >  <style> always will be write inside <haed> tag.

2)  External Css
     ---------------------
           > External Css means we will create spreate file where we write the css code
           >  External Css extension (.css)  , in external file no need to <style> tag

       How to link external file in Html
       --------------------------------------------->
        syntex--->   <link rel="stylesheet" href="fileName">
        example->   <link rel="stylesheet" href="style.css">            

3)   Inline Css    
     ----------------
          >  Inline css we can write the css code inside particular tag within style property
          syntax---> <h1 style="propertyName:value;">Hello</h1> 
          example-->  <h1 style="color:red;">Hello</h1>

Selectors in Css
==============>   With the help of selector we can target the HTML element.
        

1.  Id selector (#)
-------------------------
    > In the case of id selector we can create only one id to the html elment 
    >  id selector denoted by (#) symbole   

                        <div id="t1">welcome</div>

         example-->      #t1{
                                          color:red;
                                       }

2.  Class selector (.)
-------------------------
    > In the case of class selector we can create multiple class to html elment 
    >  class selector denoted by (.) symbole   

                      <h1 class="t1">welcome</h1>

         example-->      .t1{
                                          color:red;
                                       }

             
3.  TagName selector (tagName)
-------------------------
    > In the case of TagName  selector we will target html elment by tagname.
    >  TagName selector denoted by (TagName (h1)) symbole  

                <h1>welcome</h1>

         example-->      h1{
                                          color:red;
                                       }
 




