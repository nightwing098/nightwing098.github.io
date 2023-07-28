<html>
<head>
<style>
body {
  background-color: #000000;
  font-family: Arial, sans-serif;
}

h1 {
  color: #FFFFFF;
  text-align: center;
  animation: rainbow 3s infinite;
}

p {
  color: #FFFFFF;
  text-align: center;
  animation: fade-in 2s;
  cursor: pointer;
}

a {
  color: #00FFFF;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
  color: #FFFFFF;
}

img {
  display: block;
  margin: 0 auto;
  max-width: 100%;
}

/* The rainbow animation code */
@keyframes rainbow {
  0% {color: grey;}
  34% {color: gray;}
  68% {color: lightsteelblue;}
  100% {color: lightskyblue;}
}

/* The fade-in animation code */
@keyframes fade-in {
  from {opacity: 0;}
  to {opacity: 1;}
}
</style>
</head>
<body>

<h1 class="center">Welcome to RITESH YADAV's github.io page!</h1>

<p class="center" onmouseover="this.style.color='#FFFFFF'" onmouseout="this.style.color='#000000'">You can visit my GitHub profile by clicking <a href="https://github.com/nightwing098">here</a>.</p>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<script>
// This is a JS script that shows the current date and time
var date = new Date();
var dateString = date.toLocaleDateString();
var timeString = date.toLocaleTimeString();
document.write("<p class='center'>The current date and time is: " + dateString + " " + timeString + "</p>"); >

</script>
</body>
</html> 
