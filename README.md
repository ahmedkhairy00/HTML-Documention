# HTML-Documention

# **Html Basics**

 **Html** is shortcut to (**Hyper Text Markup Language**).

- **WWW**   : in 1989 invented www by Tim Berners.
- **HTML**    : also invented in 1991 By Same Person Tim Berners .
- **HTML5**   : It last version of HTML appear in 2017.
- **Hyper Text** : its like (paragraph - texts - images - lists - audio - video).
- **Through HTML we can design main structure of any website .**

 **HTML made up TAGS** 

**1 - comment** 

   and write in Html Like This 

```jsx
       <!-- this is a comment -->
```

**2 - Doctype**

   and its First line in Html Page , its to define code is Html

```jsx
 <!DOCTYPE html>
```

 **3 -  html tag**

  its write after define file as HTML , and it first basic code

```jsx
  <html>
  </html>
```

**4 - head tag** 

  the head code contain address of page on title tag

  and to link to CSS file and JavaScript file and fonts and icons in link tag .

```jsx
 <head>
 <title> Head tag </title>
 <link src="style.css">

</head>
```

**5 - title tag**

   the code that contain web address name , and it inside head tag

```jsx
   <head>
    <title> Head tag </title>
  </head>
```

**6 - body tag** 

 the main code that contain all code of web page content like (texts , images , paragraph).

```jsx
<body>
    <h1> Head One </h1>
</body>
```

**7 - Heading from <h1> to <h6>**

 its main Heading and have 6 size the bigger <h1> , and the smallest <h6>

```jsx
 <h1> Head one </h1> 
 <h2> Head two </h2> 
 <h3> Head three </h3> 
 <h4> Head four </h4> 
 <h5> Head five </h5> 
 <h6> Head six</h6> 
```

**8 - paragraph**

 its write paragraph in web page

```jsx
 <body>
   <p> This is My First Pararaph </p>
 </body>
```

**9 - breaking tag**

 its code we can make empty line in Html File 

and it is a Single tag

```jsx
 <body>
   <p> This is My First Pararaph </p>
   <br>   <!-- this is Breaking tag or empty line -->
 </body>
```

**10 - breaking tag by horizontal line**

 its code we can make empty line in Html File in Horizontal page

and it is a Single tag

```jsx
 <body>
   <p> This is My First Pararaph </p>
   <hr>   <!-- this is Breaking tag or empty line -->
 </body>
```

**11 - anchor tag define hyperlink** 

its code to relate any web page to another web page

and we write the link in href (hyperlink reference (source)  ).

```jsx
 <body>
   <p> This is My First Pararaph </p>
   <a href="https://www.google.com" target="blank"> Google </a> 
 </body>
```

 and There Some Preparties  to add for anchor tag <a target = blank , parent , self ,top>

 **blank : open the web page in another page** 

**parent , self , top  : its open the same web page**

**12 - link tag** 

it used for relate html file to external file like (style.css) and its stylesheet.

```jsx
 <head>
 ****<link rel="stylesheet" type="text/css" href="css/style.css">

</head>
```

rel : Definition stylesheet

type : type of file 

href : Location of file

**13 - meta tag**

 its  a single tag , and we can through it choose encode of charset 

and the best encode is (utf-8) because it support Arabic and English

and we can define the web page and content of the website in content and its appear in search of google under the website name  

```jsx
 <head>
 <meta charset="utf-8" >
 <meta name="description" content="My portifilio , Iam Front-End Deceloper you can alos download my CV fom mY website">
 <meta name="author" content="Ahmed Khairy" >

</head>
```

**14 - style tag**

 this tag be in head tag , and its write in it CSS properties 

```jsx
 <head>
    <style>
      body{
           background-color : red;
           font-size : 16px;
          }
    </style>
</head>
```

**15 - div tag**

 its like Box Or Section And we can make in it any thing we need 

and its in body tag

```jsx
  <body>
      <div>  Hello World From First Div  </div>
  </body>
```

**16 - span tag**

 its like div but it better use in small things like this

```jsx
 <body>
      <div>  Hello World From <span>First Div </span> </div>
  </body>
```

**17 - header tag**

its used for definition header of the website

and always contain Logo and main List in nav tag

```jsx
<body>

 <header> 
  <div class="logo"> Logo </div>
  <nav>
     <ul>
       <li>Home </li>
       <li>About </li>
       <li>Contact us </li>

     </ul>
  </nav>
 </header>
</body>

```

**18 - nav tag** 

 its code that contain main list and its called navigation and  this code be in body tag

```jsx
<body>

 <header> 
  <div class="logo"> Logo </div>
  <nav>
     <ul>
       <li>Home </li>
       <li>About </li>
       <li>Contact us </li>

     </ul>
  </nav>
 </header>
</body>

```

**19 - main tag** 

and this code used for main content of the website and we can replaced by div tag

but for best practice we must used main tag from HTML5 

```jsx
<body>
 <main>
   <h1> main Content </h1>
   <p> this is main pargpaph </p>
</main>
</body>

```

**20 - section tag**

its the same like div tag but it used for definition specific place in website and it comes with HTML5

and it used in body tag

```jsx
 <body>
 <section>

  <h2> section Heading </h2>
  <br>

</section>
</body>
 

```

**21 - article tag** 

its similar to section tag but it used for article in website and used in body tag

```jsx
 <body>
 <article>

  <p> My name Ahmed Khairy Ali Iam Learning Web Design</p>

</article>
</body>
 
```

**22 - aside tag**

this tag used in side of website however right or left and used in body tag to

```jsx
 <body>
 <aside>
   <ul>

    <li> ID </li>
    <li> name</li>
    <li> Phone Number</li>
   </ul>
</aside>
</body>
 
```

**23 - details tag**

new feature in HTML5 used for appear the content write into him and have arrow to appear the content

```jsx
 <details>
   <summary> Programming Language </summary>
   <p> Hyper Text Markup Language </p>
   <p> Cascading style sheet</p>
</details>
```

**24 - dialog tag**

its used for known for dialog and window

```jsx
<dialog>
   this is My dialog
</dialog>
```

**23 - summary tag**

its first first code in details tag it (summary)

```jsx
 <details>
   <summary> Programming Language </summary>

</details>
```

**23 - data tag**

its contain some data , and it used in shop to give every product specific number via value 

```jsx
 <data value="1">
   product 1

</data>
```

**27 - footer**

its the footer for web page, and it part of web page like header and section , and it write into it social media link 

```jsx
<footer>
<img class="log" src="image/logo">
<i src="facebook"> facebook </i>

</footer>
```

**28 - ul tag (unorderd List)**

its list have data without and order , and items into it write in <li> tag

```jsx
<h2> Programming Language </h2>
<ul>
	<li> Html </li>
	<li> Css </li>
	<li> JavaScript</li>
	<li> BootStrap</li>
</ul>
```

**29 - ol tag (orderd List)**

its list have data and orderd , and items into it write in <li> tag

```jsx
<h2> database Language </h2>
<ol>
	<li> Html </li>
	<li> Css </li>
	<li> JavaScript</li>
	<li> BootStrap</li>
</ol>
```

**30 - li tag (List Item)**

its the items in lists however ul or ol  and exist in above example

```jsx
<ul>
	<li> Html </li>
	<li> Css </li>
</ul>
```

**31 - dir tag (dictionary list)**

its dictionary list and write like ul and ol 

but it not supported in HTML5

```jsx
<dir>
	<li> names </li>
	<li> Address </li>
</dir>
```

**32 - dl tag (description list)**

its list to describe items in the list , and it used with it (dt) .

(dt) → contain item

 (dd) → describe item

```jsx
<dl>
	<dt> coffe </dt>
	<dd> with no suger and with suger</dd>

	<dt> Milk </dt>
	<dd>Hot Milk , Cold Milk</dd>
</dl>
```

**33 - dt tag**

 contain item that will describe

**34 - dd tag**

 contain describe of the item.

**35 - img tag**

its tag that allowed us to add image in web page , and must enter image path in (src).

and it single tag like this <img> 

```jsx
<img src="images/myphoto.jpg" alt="myphoto" >
```

**36 - map tag** 

it used with img tag , but property name must be the same name in img properties

- and its include <area> tag , because we can select places we can click to go specific website

```jsx
<img usemap="lol">
<map name="#lol">
   <area shape="circle" coords="30,40,270,350" href="https://www.google.com" alt="" >
</map>

```

**37 - area tag**

it the place we selected in map tag that connected with specific img ,  via value of (coords)

```jsx
<img usemap="lol">
<map name="#lol">
   <area shape="circle" coords="30,40,270,350" href="https://www.google.com" alt="" >
</map>

```

**38 - canvas tag**

it used in graphic by use JavaScript and write in HTML like this way

```jsx
<canvas id="canvas" width="300" height="300"> </canvas>
```

**39 - figcaption tag**

this for known caption for element (figure) and write like this

```jsx
<figcaption> </figcaption>
```

40**- figure tag**

this element which contain figcaption tag and write like this

and this writing appear under the image

```jsx
<figure>
 <img src="myphoto.jpg">
<figcaption> this is my photo </figcaption>

</figure>
```

**41- picture tag**

that known place of group if image , and we can add more than one image 

```jsx
<picture> 
<source media="(min-width:650px)" srcset="img.jpg">
<source media="(min-width:450px)" srcset="img.jpg">

</picture>
```

**42 - svg tag**

it used for graphic ,its mean (scalable vector graphic) , and it two demintion and supported from animation 

and it used width and height 

```jsx
<svg width="100" height="100"> 

<circle cx="50" cy="50" r="40" strok="green" strok-width="4" fill="yellow"/>
</svg>
```

**43 - audio tag** 

this tag allow us to add voice like Quran ,and songs

and we must write the sounds by its path in src 

and its have this properties (controls, auto play, loop , muted, preload)

```jsx
<audio src="fady-shawya.mp3" controls autoplay loop muted preload>
```

**44 - source tag**

this code know more than thing in multimedia like(sounds, videos , etc)

```jsx
<source src="fady-shawya.mp3" controls autoplay loop muted preload>
<source src="fady-shawya.mp4" controls autoplay loop muted preload>
```

**45 - track tag**

its used with audio and video tags to add subtitles

```jsx
<track kind="subtitles" src="samplesubtitlrs_en.srt" srclang="en">
```

**46 - video tag** 

this tag allow us to add videos in web page

```jsx
<video src="fady-shawya.mp4" controls autoplay loop muted preload poster="poster.jpg">
```

**47 - form tag**

this code of form who used in login and sign up pages 

and have specific property like action

```jsx
<form action="index.html" method="Post||Get" >
</form>
```

**48 - Input tag** 

this tag  add to web page some different elements by used property type

and have another properties like name , value, 

and we can add in type property all this element (text,putton,email,checkbox,date,color,datetime-local,file,hidden,image,month,number,password,radio,range,reset,search,submit,tel,time,url,week)

```jsx
<input type="text" name="text-place">
<input type="putton">
<input type="file">
<input type="submit">
<input type="color">
<input type="password" placeholder="enter password">
```

**49 - textarea tag**

its a specific space to user to write in web page 

and we can resize its width and height

```jsx
<textarea name="name" rows="8" cols="80" > </textarea>
```

**50 - button tag**

its tag allowed to create button in web page

its type can be (button , menu , reset , submit)

```jsx
<button type="button" name="log in" > Button 1 </button>
```

**51 - select tag** 

its make us to create droplist ⇒ to chasse from it 

```jsx
<select name="front" class="menu1" >

</select>
```

**52 - optgroup tag**

its code write into select tag to divide it to groups 

and optgroup contain option tag to select from it 

```jsx
<select name="front" class="menu1" >
<optgroup label=""> </optgroup>

</select>
```

**53 - option tag**

its tag we can select from it 

and it be in droplist in optgroup tag

```jsx
<h2> Programming language> </h2>
<select name="front" class="menu1" >
<optgroup label="Front-End-Language">

<option value=""> Html </option>
<option value=""> Css</option>
<option value=""> JavaScript</option>

</optgroup>

</select>
```

**54 - label tag** 

this tag that we used for define input if text or password or email by this label

and we can connect the label to the input by use for and must input name be the name in property for in label

```jsx
<label for="name"> UserName :</label>
<input type="text" name="name">
```

**55 - fieldset tag** 

it contains group of connected elements into form like (email,textarea).

```jsx
<fieldset>
      <input type="email" name="email" placeholder="enter your email">
      <textarea row="8" cols="80" placeholder="enter your message"> </textarea>
</fieldset>
```

**56 - legend tag**

it  known the address of elements in fieldset  , its like code above 

```jsx
<fieldset>
      <legend>Contact With Me</legend>
      <input type="email" name="email" placeholder="enter your email">
      <textarea row="8" cols="80" placeholder="enter your message"> </textarea>
</fieldset>
```

**57- datalist tag** 

its known list of group of  elements , and this elements in list by use option tag

```jsx
<label> Select Your Car </label> 
 <datalist>
       <option> Mercides </option>
			<option> BM </option>
			<option> toyata </option>
~~~~</datalist>
```

**58 - output tag**

this code used with form and input tag , and the result be in output tag

```jsx
<form oninput="x.value = parseInt(a.value) + parseInt(b.value)">
<input type="range" id="a" value="50">
<input type="number" id="b" value="25">
<output name="x" for="a b"> </output>
<form>
//// Very Important HTML Code
```

**59 - frame tag**

Not Supported in HTML5 , and replaced by (iframe) tag

```jsx
<frame> </frame>
```

**60 - frameset tag**

Not Supported in HTML5 , and replaced by (iframe) tag

and it was used for divide web page by use (frame)

```jsx
<frameset> </frameset>
```

**61 - noframes tag**

Not Supported in HTML5 , and replaced by (iframe) tag

```jsx
<**noframes**> </**noframes**>
```

**62 - iframe tag**

this code use to add web page in another web page , and it used to show location on google map

```jsx
<iframe src="https://www.google.com" width="800px" height="800px">
 </iframe>
```

**63 - table tag**

this code for create table in web page

```jsx
<table> </table>
```

**64 - caption tag**

this code define table subject or table data 

```jsx
<table>
   <caption> Egyptian league standings<caption>
 </table>
```

**65- th tag**

this is define headers cell in table , and its normally Bold

```jsx
<table>
   <caption> Egyptian league standings<caption>
   <th> Standing </th>
   <th> Win</th>
   <th> Lose </th>
   <th> Draw</th>

 </table>
```

**66 - tr tag**

this code create table row , and contain cells in (td tag)

```jsx
<table>
   <caption> Egyptian league standings<caption>
   <th> Standing </th>
   <th> Win</th>
   <th> Lose </th>
   <th> Draw</th>

		<tr>
        <td> Al Ahly </td>
        <td> 9 </td>
****        <td> 0</td>
****        <td> 1</td>

		****</tr>

 </table>
```

**66 - td tag**

this code to create cell in table

colspan → to marge cells in column

rowspan → to marge cells in row

```jsx
<table>
   <caption> Egyptian league standings<caption>
   <th> Standing </th>
   <th> Win</th>
   <th> Lose </th>
   <th> Draw</th>

		<tr>
        <td> Al Ahly </td>
        <td> 9 </td>
****        <td> 0</td>
****        <td> 1</td>

		****</tr>

 </table>
```

**67 - thead tag** 

this groups the header tags in table

```jsx
<table>
 <thead>
		 <th> Standing </th>
	   <th> Win</th>
	   <th> Lose </th>
	   <th> Draw</th>
 </thead>
</table>
```

**68 - tbody tag**

this groups the body tags in table

```jsx
<table>
 <tbody>
		<tr>
        <td> Al Ahly </td>
        <td> 9 </td>
****        <td> 0</td>
****        <td> 1</td>

		****</tr>
	 </tbody>
 </table>
```

**69 - tfoot tag** 

this groups the footer in table

```jsx
<table>
 <tfoot>
		<tr>
        <td> Al Ahly </td>
        <td> 9 </td>
****        <td> 0</td>
****        <td> 1</td>

		****</tr>
	 </tfoot>
 </table>
```

**70 - col tag**

this code create special property for every column in the table 

by use (colgroup tag)

```jsx
<col span="2">
```

**71 - colgroup tag**

this code create special property for every column in the table 

by use (colgroup tag)

```jsx
<colgroup>
	<col span="2" style="background-color : red">
	<col span="2" style="background-color : blue">
</colgroup>
```

**72 - script tag**

this code allowed us to use javaScript File into html page

and we can add this file in (head, body) tags , But Best practice add script tag before (</body>)

```jsx
<script src="js/main.js" type="text/javascript"> </script>
 // Best Place To but javaScript file
</body>
```

**73 - noscript tag**

this code allow us to appear message to user that his browser don't support JavaScript

```jsx
<noscript>your browser dosent support javaScript </noscript>
```

**74 - applet tag**

Not Supported in HTML5 , and Replaced by (embed , object , audio , video) tags

**75 - embed tag**

this code we can add audio ,video and text to html page 

by select type of file and file path 

but best practice use that tags (audio , video , input type=”text” )

```jsx
<embed type="video/mp4" src="video1">
<embed type="audio/mp3" src="audio">
<embed type="text/txt" src="blog/text1">
```

**76 - object tag**

used for add external thing like (HTML page , Minu , Sound , Plugin , Video)

```jsx
<object type="" data="File.source">

</object>
```

**77 - param tag**

short of paramter tag and if define paramter for object 

its known special property for object and gived it value on value property

```jsx
<object type="" data="video.mp4">
  <param name="autoplay" value="true">
</object>
```

**78 - acronym tag** 

not supported in HTML5 , and replaced by (<abbr>) tag

**79 - abbr tag**

its abbreviation tag , and its appear the name of thing when we hover ot. 

```jsx
<abbr title="cascading style sheet"> Css </abbr>
```

**80 - address tag**

this code allow us to define of author of website , article owner  , or special thing

```jsx
<address class="author">
Ahmed Khairy<br>
48 St , Giza , Bargile , 16576 <br>
More Informtion
</address>
```

**81 - b tag** 

its tag for make text Bold , And Rather use <strong> tag

```jsx
<b> Bold Text </bold>
```

**82 - bdi tag** 

its when we need change direction for little text from long text

```jsx
<h1> This is Heading One <bdi dir="rtl"> This Oppiste Direction</bdi></h1>
```

**83 - bdo tag**

Its Override the current text direction

```jsx
<p> This is Heading One <bdi dir="rtl"> This Oppiste Direction</bdi></p>
```

**84 - big tag**

Not Supported in HTML5 , and replaced by CSS properties

**85 - blockquote tag**

its code for Quote of someone

```jsx
<blockquote cite="url(www.google.com)">
Google is Amazing Website
</blockquote>

```

**86 - center tag**

not Supported in HTML5 , and was centered text

```jsx
<center> This Is Center Text</center>
```

**87 - cite tag**

define little tag of the work

```jsx
**<cite> this is little </cite>**
```

**88 - code tag**

define apiece of computer code

```jsx
**<code> this is my code </code>**
```

**89 - del tag**

define the text has been deleted from a document 

```jsx
**<del> this is deleted line</del>**
```

**90 - dfn tag**

define termin the content

```jsx
**<p> <dfn>Css </dfn> is The Standret style sheet</del>**
```

**91 - em tag**

define emphasized text or itlatic text 

```jsx
**<p>this is  <em>Awsom </em></del>**
```

**92 - font tag**

Not Supported in Html5

**93 - i tag**

crate itlatic text

```jsx
**<i> this is itlatic text </i>**
```

**94 - ins tag**

define some text has been inserted 

```jsx
**<ins> this is inserted text </ins>**
```

**95 - kbd tag**

define keyboard input

```jsx
**<kbd> this is text </knd>**
```

**96 - mark tag**

its make highlight text 

```jsx
**<mark> this is text </mark>**
```

**97 - meter tag**

define a scalar measurement within aknown range 

```jsx
<meter value="50" min="" max="100"> </meter>
```

**98 - pre tag**

define preformatted tag

```jsx
<pre> some text </pre>
```

**99 - progress tag**

represent the progress of task

```jsx
<progress value="70" max="100"> 70% </progress>
```

**100 - q tag**

define a shorcut of quotation 

```jsx
<q cite=""> The Title </q>
```

**101 - rp tag**

define what to show in browser that dont support ruby annotations 

```jsx
<rp> This is text  </rp>
```

**102 - rt tag**

define an explanation / pronation of characters (for east Asian typography)

```jsx
<rt> This is some  text  </rt>
```

**103 - ruby  tag**

define a ruby annotation  (for east Asian typography)

```jsx
<ruby> This is some  text  </ruby>
```

**104 - s tag**

define text is not longer correct 

```jsx
<s> This is some  text  </s>
```

**105 - samp tag**

define sample output  from a computer progress 

```jsx
<samp> This is some  code</samp>
```

**106  - small tag**

define smaller text 

```jsx
<small> This is small  text</small>
```

**107 - strike tag** 

define strike through text , not supported in HTML5

**108 - strong tag**

define important text , and make it bold 

```jsx
<strong> This is Important</strong>
```

**109 - sub tag**  

define subscribed text

```jsx
<sub> This is Important</sub>
```

**110 - sup tag**

define superscripted text 

```jsx
<sup> This is superscripted</sup>
```

**111 - template tag**

define a container for content that should be hidden when the page loading

```jsx
<template id=""> </template>
```

**112 - time tag**

define specific time od (date time)

```jsx
<time> 10:00 </time> <br> <br>
<time datetime="2022-04-6"> 10:00 AM </time>
```

**113 - tt tag**

define teletype text not supported in HTML5

**114 - u tag** 

to create line under text 

```jsx
<u> underline text </u>
```

**115 - var tag** 

define variable 

```jsx
<var> some text </var>
```

**116 - wbr tag** 

define a possible linebreak

```jsx
<wbr>
<h1> this is Heading one </h1>
<wbr>
<wbr>

```

## Finish Html Document Sheet
