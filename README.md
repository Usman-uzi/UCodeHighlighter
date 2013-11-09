UCodeHighlighter
================

A very nice JQuery plugin for syntax highlighting for your code.
Its usage is very easy and simple.
Have a look how it beautify your code.


<img src="http://www.usmanbackup.somee.com/image/syntaxhighlighter/V1.0.0.0.png"/>

<br/>

Working on its first version , going to release very soon for public use :)

First version has been complete and working..

To use this on your page you must do follwing steps :

First include scripts and style sheet in header of your page :

<head>
<title>jQuery plugin: code highlighting demonstration</title>
<script src="published/jquery-1.6.3.min.js"></script>
<!--<script src="published/UCodeHighlightner.js"></script>
<script src="script/uhighlight.js"></script>
<link href="published/hilightstyle.css" type="text/css" media="screen" rel="stylesheet">-->
<script src="http://www.usmanbackup.somee.com/script/UCodeHighlightner.js"></script>
<link href="http://www.usmanbackup.somee.com/script/hilightstyle.css" type="text/css" media="screen" rel="stylesheet">

</head>

Second step is , place you code in a <div > with display none , i.e.

<div id="data" style="display:none;" >

your code here........

</div>

Third step must be , use following chunck of code on your page:

<div>
<div id="line_number" class="counting_div_wrap"></div>
<div id="main" class="main"></div>
<div style="clear:both;"></div>
</div>


The last step is to use js to process your code i.e. 

<script type="text/javascript">
// script for on page code processing
$("#main").highlight($("#data").html(),$("#line_number"));		
</script>


That's all , you are done :)
