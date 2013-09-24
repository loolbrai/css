css
===

css training


------------------------------------------------------
<link rel="stylesheet" type="text/css" href="http://zingclub.in/master/css/jquery.autocomplete.css" />

-----------1.inside 2 tybe :-------------h1 tag called

  <!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Untitled Document</title>

<style>
h1 {color:rgb(51,204,153);}
</style>

<body leftmargin="0" topmargin="0" marginwidth="0" marginheight="0">

<h1 style="color:#9797979">hihihihi </h1>
</body>
</html>


----there are 3 type ---

elements ,class,id

<h1 class="intro" id="header">Css training</h1>

h1 is elements

h1{color:#7789}

class is class selector
.intro {
color:#i9u9

}

id is id selector

#header{
color:#3e334;
}

-------------------
article inside image:

<style>

h1 {color:rgb(51,204,153);}

img{float:left;
both:clean;}
</style>

<body leftmargin="0" topmargin="0" marginwidth="0" marginheight="0">
<article>
<div class="a">a</div>
<img src="../d.jpg" />
<p class="iji">As religion was suppressed by the Soviets, Dandaron was brought to court three times and spent a significant part of his life in prison camps. First, he was arrested in 1937 and released in 1943, then arrested again in 1948 but released with political rehabilitation in 1956. He actively wrote and taught on Buddhism while imprisoned, and some of his ardent followers started from camps. There, he also had a number of Russian philosophers and other scholars, as well as Buryat lamas, to exchange opinions and gain knowledge of European philosophy and history he widely refers to in his writings. Principally, Vasily Seseman, a philosophy professor from Lithuania who was imprisoned from 1950 to 1956, became his friend and tutor in European philosophy, starting Danrdaron's appreciation of Kantian thought.

After 1956 his friends from <img src="" />the Oriental Studies Institute in Leningrad made attempts to give him a job in the institute library, but were not allowed to. In 1957, Dandaron began working for the Buryat Institute of Social Sciences in Ulan-Ude. He wrote extensively on <img src="../d.jpg" />Tibetan studies and translated religious and historical literature of Tibet into Russian, publishing over 30 articles and other works. His religious works came to public as samizdat.

In 1960 - early 1970s the community of his followers grew to several dozen people, mostly from St Petersburg, Moscow, Tartu and Vilnius. His principal community was in St Petersburg (then Leningrad) where in 1972 he was arrested and tried for the organization of a Buddhist sect. Some of his students were arrested as well, but never tried. Mostly they were released, while some were placed in mental health clinic. Dandaron got 5 years of labor camp where he continued to write about, teach and practice Buddhism. Having warned his neighbors, in the camp in Vydrino he experienced samadhi several times, stopping his heartbeat and breath at will for days. In 1974 he did not return from the samadhi.
References</p>
</article>


2 images for float left and float right:

<style>

h1 {color:rgb(51,204,153);}

img{float:left;
width:100;
both:clean;}
1.{
	float:left;}
2.{
	float:right;}
</style>

<body leftmargin="0" topmargin="0" marginwidth="0" marginheight="0">
<article>
<div class="a">a</div>
<img class ="1" src="../../Pictures/d.jpg" />
<img class="1" src="../../Pictures/d.jpg" />
<p class="iji"> 
</article>
<h1 style="">hihihihi </h1>
</body>
</html>


clear float:

sometime not more space so we handle another div that why clear float will come:

 <body>
<div>
<img src="../../Pictures/d.jpg"/>
<p>sddddsdsdds</p>
<div class="clear"></div>
</div>
</body>
</html>

good code for:

.group:before,
.group:after {
content: "";
display: table;
}
.group:after {
clear: both;
}
.group {
zoom: 1; /* IE6&7 */
}
<style>
.group:before,
.group:after {
content: "";
display: table;
}
.group:after {
clear: both;
}
.group {
zoom: 1; /* IE6&7 */
}
</style>


 <body>
<div class="group">
<img src="../../Pictures/d.jpg" alt="Skiing!" />
<p>To successfully ski, simply do not fall.</p>


nested selected :


<article class="featured">
<p>Dang, it's cold up here!</p>
</article>
.featured {
color: #0000ff;
}
.featured p {
color: #fff;
}


over right which will win ???


2
Inheritance & Specificity
 

elements
class
header
inline style sheet
p{color:#fff !important}


#content  {
color: rgb(255,0,0);
}
.featured {
color: #777;
}
</style>
<body>
<section id="content">
<p class="featured">Free coffee with ski rental.</p>
<p>Choose from 48 different ski colors.</p>
</section>


------------------------------------------------------------------
.big-margin {
    background: none repeat-y fixed 51px 57px dimgray;
    border: 277px outset #FFCCCC;
    margin: 144px;
}


<head>
    <title>
        Style Tag
    </title>
<style>
.big-margin {
    border: 20px solid #ccc;
    background: lightBlue;
    margin: 20px;
}
</style>

</head>

<body>
<div class="big-margin">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras laoreet dolor at diam facilisis vel ultrices nunc pretium. Nam urna velit, convallis ut vulputate vitae, posuere at erat. Mauris laoreet consectetur sodales. Duis est ligula, pellentesque sed blandit placerat, posuere ut tortor. Duis fringilla sapien a turpis imperdiet nec scelerisque risus lobortis. Nullam porta congue elit in consequat. Fusce vitae sapien dictum orci tincidunt suscipit pulvinar non tortor. Proin blandit fermentum sollicitudin. Integer tincidunt condimentum urna non aliquet. In eget tellus sapien. Morbi auctor dolor sit amet nisi gravida sollicitudin. Ut consequat, purus vitae pharetra hendrerit, nibh elit cursus est, sed consequat magna tellus ac leo. Nullam nisi ligula, blandit ornare viverra tristique, placerat aliquam turpis. Sed quis eros sem, volutpat iaculis augue. Fusce aliquam, mauris ut ullamcorper iaculis, nibh mi malesuada urna, condimentum lobortis neque felis quis libero.

Suspendisse potenti. Donec tempus orci faucibus ligula varius pretium. Nam vitae iaculis turpis. Mauris vel accumsan leo. Praesent et enim justo. Nulla fermentum, ipsum a porttitor dictum, ipsum libero fermentum odio, eget pharetra nunc odio a nulla. Vestibulum erat odio, venenatis a facilisis et, aliquam at leo. In eu sollicitudin orci. Morbi egestas, neque ut egestas dapibus, dui enim egestas est, aliquet vulputate massa massa non nisi. Integer eu leo non est auctor porttitor eu in sem. Maecenas turpis lacus, tempus at feugiat dictum, laoreet eu lectus. Nunc faucibus sodales dictum.

Curabitur scelerisque purus id risus adipiscing rutrum. Nulla facilisi. Curabitur non sem sed diam euismod dictum. Pellentesque molestie facilisis nulla, sed porttitor felis posuere ac. Aenean laoreet ligula sit amet dui viverra volutpat. Nullam arcu velit, malesuada quis consectetur id, semper eget mi. Integer at dolor sed metus porta sagittis. Proin a mauris sit amet libero accumsan tincidunt. Quisque facilisis tempor mauris nec fermentum. Vivamus ullamcorper ultrices lectus a tincidunt. Curabitur tempus faucibus justo quis lacinia. Suspendisse potenti.

</p>
</div>
</body>
</html>


------------------------------------------------------

1.margin(first)
2.border(secound)
3.padding(inside content)



----------------------------------------------------------------------------------

<span></span> height text for background , border, 

------------------------------------------------------------------------------------------------------------

comments:

<!-- you can type any letter inside the comment field -->


-------------------------------------------------------------------------------------------------------------
css comment:

/* you can type any letter inside the comment field 
*/

----------------------------------------------------------------------------------------------------------------


text align:center;

the text will came from center


----------------------------------------------------------------------------------------------------------------

link state:


a:link{
color:red;
}

-------------------------------------------------------

link example
<!DOCTYPE html>
<html>
<head>
<style>
a:link {color:red;}    /* unvisited link */
a:visited {color:green;} /* visited link */
a:hover {color:white;}   /* mouse over link */
a:active {color:blue;}  /* selected link */
</style>
</head>

<body>
<p><b><a href="default.asp" target="_blank">This is a link</a></b></p>
<p><b>Note:</b> a:hover MUST come after a:link and a:visited in the CSS 
definition in order to be effective.</p>
<p><b>Note:</b> a:active MUST come after a:hover in the CSS definition in order 
to be effective.</p>
</body>
</html>

---------------------------------------------------------------------
p.first:first-line{
	background-color:rgb(0,0,102);
	}
-----------------------------------------------------------------------
input css :

input[type="text"]{
width :28px;		
		}
		
		------------------------
		
