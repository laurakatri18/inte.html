<head><title>Laura</title></head>


<body>

<h1> <em> <strong> <mark>Estrazioni</strong></em></mark></h1>
<h4> Chi sarà il fortunato oggi?</h4>
<input id="pulsante" type="button" value="ESTRAIMI" onclick="funzione();"/>
<h2 id="numero">Numero</h2>
<h3 id="compagno">Compagno</h3>
<img src="http://www.applicazioni.me/tuttodisegni/files/2012/07/maestra-lavagna.jpg" style="position:absolute;left:200px;top:30px;height:700px">

<ol>
  <li>Laura</li>
  <li>Yoel</li>
  <li>Dalia</li>
  <li>Jordan</li>
  <li>Daniel</li>
  <li>Tommaso</li>
  <li>Limor</li>
  <li>Sara</li>
  <li>Raphael</li>
  <li>Josh</li>
</ol> 

</body>

<script>

var compagni= ["Laura", "Yoel", "Dalia", "Jordan", "Daniel", "Tommaso", "Limor", "Sara", "Raphael", "JOsh"]

function funzione(){
var z = Math.floor((Math.random() * 10) + 1);
	document.getElementById("numero").innerHTML = z;

if (z==1){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==2){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==3){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==4){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==5){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==6){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==7){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==8){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==9){
document.getElementById("compagno").innerHTML=compagni[z-1];
}

if (z==10){
document.getElementById("compagno").innerHTML=compagni[z-1];
}


}

</script>

</html>
