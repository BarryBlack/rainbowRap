# rainbowRap
this is a rap aboout rainbows


easy booking lawn mowing app. ?? 
google api were the lawn man is
alerts when in your area?

dominoes pizza tracking as a example. can I do that with lawns


https://www.yourgreenpal.com/
example of app


when lawn mower in the area you get a alert.


<!DOCTYPE html>
<html>
<body>

<p>Click the button to get your coordinates.</p>

<button onclick="getLocation()">Try It</button>

<p id="demo"></p>

<script>
var x = document.getElementById("demo");

function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition);
  } else { 
    x.innerHTML = "Geolocation is not supported by this browser.";
  }
}

function showPosition(position) {
  x.innerHTML = "Latitude: " + position.coords.latitude + 
  "<br>Longitude: " + position.coords.longitude;
}
</script>

</body>
</html>
