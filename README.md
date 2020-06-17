# sentence_function

<html>
<body>

<p>Click the button to return the number of characters in the string "Lamar Jackson is Amazing!".</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
  var str = "Lamar Jackson Is Amazing!";
  var n = str.length;
  document.getElementById("demo").innerHTML = n;
}
</script>

</body>
</html>
