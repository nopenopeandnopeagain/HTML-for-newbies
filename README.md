# HTML for newbies

<html>
    <head>
        <meta charset="utf-8">
        
    </head>
    <style>
    body {
        background:yellow;
    }
    .CLASS {
        color:red;
         font-family:cursive;
         font-size:24px;
         font-style:italic;
         font-weight:bold;
    }
    #P1 {
        color:red;
        font-family:cursive;
        font-size:24px;
    }
    .size {
        font-family:cursive;
        font-size:19px;
        color:blue;
    }
    .P2 {
        font-family:sans-serif;
        color:blue;
    }
        
        
        
        
    </style>
    
    <body>
    <h1 class="CLASS">HTML for newbies! By: Zachary and Chloe</h1>
    <p id="P1"> Contents:</p>
    <p class="size"> <a href="#jump">Chapter 1: What is HTML?</a></p>
    <p  class="size"> <a href="#jump2">Chapter 2: Basics of HTML!</a> </p>
    <p class="size"> <a href="#jump3">Chapter 3: Who made HTML? </a> </p>
    <p class="size"> <a href="#jump4">Chapter 4: What is CSS?</a> </p>
    <p class="size"> <a href="#jump5">Chapter 5: Intro to CSS!</a></p>
    <p class="size"> <a href="#jump6">Chapter 6: ID's! </a> </p>
    <p class="size"> <a href="#jump7">Chapter 7: Classes! </a></p>
    <br> 
    <h1 class="size" id="jump">Chapter 1: What is HTML? </h1>
   <p class="P2">Hypertext Markup Language is the standard markup language for creating web pages and web applications. With Cascading Style Sheets and JavaScript, it forms a triad of cornerstone technologies for the World Wide Web.  </p>
   <p> <a href="https://en.wikipedia.org/wiki/HTML">From Wikipedia</a> </p>
   <h3 class="size" id="jump2">Chapter 2: Basics of HTML!</h3>
   <p class="P2"> All HTML documents must start with a document type declaration: !DOCTYPE html

The HTML document itself begins with html and ends with html!

The visible part of the HTML document is between body and body.
HTML headings are defined with the h1 to h6 tags. h1 defines the most important heading. h6 defines the least important heading.
HTML paragraphs are defined with the p tag.
HTML links are defined with the a tag.


 </p>
 
 <a href="https://www.w3schools.com/html/html_basic.asp">From W3schools</a>
 <p> </p>
 <h1 class="size" id="jump3"> Chapter 3: Who made HTML?</h1>
 <p class="P2"> Tim Berners-Lee is the inventor of the Web. (HTML too) In 1989, Tim was working in a computing services section of CERN when he came up with the concept; at the time he had no idea that it would be implemented on such an enormous scale. Particle physics research often involves collaboration among institutes from all over the world. Tim had the idea of enabling researchers from remote sites in the world to organize and pool together information. But far from simply making available a large number of research documents as files that could be downloaded to individual computers, he suggested that you could actually link the text in the files themselves. </p>
  <a href="https://www.w3.org/People/Raggett/book4/ch02.html"> From W3</a>
  <h4 class="size" id="jump4">Chapter 4: What is CSS?</h4>
  <p class="P2">A CSS (cascading style sheet) file allows you to separate your web sites (X)HTML content from it’s style. As always you use your (X)HTML file to arrange the content, but all of the presentation (fonts, colors, background, borders, text formatting, link effects & so on…) are accomplished within a CSS.

</p>
<a href="https://www.cssbasics.com/introduction-to-css/"> From CSS basics</a>
<h1 class="size" id="jump5"> Chapter 5: Intro to CSS!</h1>
<p class="P2"> Why not start off with how to change our background? To start, add style BEFORE the body in your editor. Then type body { background:red; } We can also use a rgb selector. background:rgb(232, 0, 0); This also results in the color red. To change the text, just do body { color:red; }. Of course, it doesn't need to be red, other colors  work too! 
(We wrote this.)


</p>
 <h1 class="size" id="jump6"> Chapter 6: ID's!</h1>
 <p class="P2"> What if you wanted to only color SOME of the text, not all of it? Well, ID's to the resuce! To use an ID put the ID in a paragraph or maybe a heading. An example: p id="ID"> Then use the style command again. Put: #(ID GOES HERE) { color:(color);
     } Boom! Only some of the text is colored! There is also something VERY similar to this. Classes! 
 </p>
 <h1 class="size" id="jump7">Chapter 7: Classes!</h1>
 <p class="P2"> Classes are almost the same as ID's. But, to declare it, you must use .(class) instead of  #(ID). </p>
 
  
  

    </body>
</html>
