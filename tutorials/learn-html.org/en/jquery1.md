Tutorial
--------
jQuery is a lightweight, "write less, do more", JavaScript library.
jQuery is just a small 20+kb JavaScript file (e.g jquery-1.2.6.min.js), you can download it from the jQuery official website.

Exercise
--------
The $() is a signature jQuery syntax. 
call back ???

What the following javascript does is when DOM elements are ready or fully loaded, execute the jQuery script to dynamic create a message and append it to html tag id “did”. It is achieved by jquery functions and call back mechanism.


Tutorial Code
-------------
<html>
<head>
<title>jQuery Hello Albany</title>

<script type="text/javascript" src="jquery-1.2.6.min.js"></script>

</head>

<body>

<script type="text/javascript">

$(document).ready(function(){
 $("#did").html("Greeting from Albany");
});

</script>


<div id="did"> </div>

</body>
</html>

Expected Output
---------------
create two divisions showing Greeting from Albany in both.  ids for two divisions should be did1 and did2 respectively.

Solution
--------

<html>
<head>
<title>jQuery Hello Albany</title>

<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

</head>

<body>

<script type="text/javascript">

$(document).ready(function(){
 $("#did1").html("Greeting from Albany");
 $("#did2").html("Greeting from Albany");

});

</script>

This is Hello World from jquery

<div id="did1"> </div>
<div id="did2"> </div>

</body>
</html>

