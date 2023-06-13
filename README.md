<!DOCTYPE html>
<html>
<body bgcolor="#839192">
<h2><u><font color="orange">JavaScript Template Literals:-</font></u></h2>
<p id="demo"></p>
<p id="demo1"></p>
<p><font color="33EAFF">Adventure. ...
Comedy. ...
Drama. ...
Horror. ...
Science ...
Fantasy.
</font>
</p>
<p> The movie"spider-man:Across the spider-Verse"shameik moore originally in english has rating 9.0
</p>
<script>
	let MovieName = "Transformers"; 
	let Starring = "Meghan Fox"; 
	let Language = "English"; 
	var Rating = "7.9"; 
	let Movie = "San Andreas"; 
	let Cast = "Dwayne Johnson"; 
	let Lang = "English"; 
	var Ratings = "8.5"; 
	let text = `The movie  "${MovieName}" starring  ${Starring} originally in ${Language} has rating of ${Rating}`; 
		document.getElementById("demo").innerHTML = text; 
	let text1= `The movie  "${Movie}" starring  ${Cast} originally in ${Lang} has rating of ${Ratings}`; 
		document.getElementById("demo1").innerHTML = text1; 
</script>
<hr>
<marquee><font color="yellow"> starring,ratings,movies movie languages details are present here<font></marquee>
<hr>
</body>
</html>
