## Front End Notes
# Html Page
> Outline a brief description of your project.
> Live demo [_here_](https://www.example.com). <!-- If you have the project hosted somewhere, include the link here. -->

## Table of Contents
* [heading Tag in HTML](#heading-Tag-in-HTML)
* [Table Tage in HTML](#Table-Tage-in-HTML)
* [List tag in HTML](#List-tag-in-HTML)
* [Hyperlink in HTML](#Hyperlink-in-HTML)
* [Form tag in HTML](#Form-tag-in-HTML)
* [Block And Inline Element or tag](#Block-And-Inline-Element-or-tag)
<!-- * [License](#license) -->


## heading Tag in HTML
<!---<h1>welcome</h1>
-<h2>welcome</h2>
-<h3>welcome</h3>
-<h4>welcome</h4>
-<h5>welcome</h5>
-<h6>welcome</h6>->>
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Table Tage in HTML
- create table in html with the help of <table> tag
  -<tr>   tag use for the Row 
  -<th>  tag use for the colomn in heading format
  -<td>  tag  also use for normal column

-example
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


## List tag in HTML
-<ul>  tag use for unorder list
-<ol>  tag use for order list
-<li>   tag use for list must be inside <ul> or <ol>
-example
     -unorder list
	  <ul>
		  <li>Apple<li>
		  <li>Banana<li>
		  <li>papaya<li>
    </ul>
  
    -orderd list	                  
  	 <ol>
		  <li>Apple<li>
		  <li>Banana<li>
		  <li>papaya<li>
     </ol>

## Hyperlink in HTML
-<a>tag  use for the craete the hyperlink
-href=""  inside href you pass the location ,where you want to send 
  -example
    <a href="home.html">Home</a> 
<!-- If you have screenshots you'd like to share, include them here. -->


## Form tag in HTML
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



## Block And Inline Element or tag
  
-Block Element
---------------------->
1. Block element cover full width and cursor put new line.

  example--->   <div>,<h1>,<p> etc

-Inline Element
---------------------->
1. Inline element cover width depend upon our content and cursor in same line.
2. In inline element we can not apply height , width,.
3. With the help of some property we can convert (inline to block,  block to inline) 
       through the css.
  
  property name:   >   display:inline;
                              >   display:inline-block;
                              >   display:block;

  example--->   <span>,<a>,<input> etc

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
