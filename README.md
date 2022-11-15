<!DOCTYPE HTML>
<html>
<head>
<h1>Music Player<h1>
<link rel="stylesheet" href="styles.css">
</head>

<script>
  //code.jquery.com/jquery.min.js
</script>

<script>app.js</script>


<style>

h1{
text-align:center;
}


div {
margin-right:5px;
margin-top:100px;
float:left;

}


button {
padding:10px;
background-color:aqua;
font-size:15px;
border:0px;
width:100px;
}


p {
    position: absolute;
        bottom: 0;
        left: 0;
}

body {
 background-image: url("images/headphones.jpg");
}
</style>

 <! -- Control Panel --> 


<div id="cp">
  <button id="play">Play</button>
</div>
 

 <div id="cp">
  <button id="stop">Stop</button>
</div>


<div id="cp">
  <button id="pause">Pause</button>
</div>


<div id="cp">
  <button id="mute">Mute</button>
</div>


<div id="cp">
  <button id="unmute">Unmute</button>
</div>


<div id="cp">
  <button id="volUp">Volume Up</button>
</div>


<div id="cp">
  <button id="volDown">Volume Down</button>
</div>

<audio id="player">
  <source src="music/song1.mp3" type="audio/mpeg">
</audio>


<p id="message">Waiting...</p>


 <! -- End of Control Panel --> 
