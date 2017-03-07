# http://yosibeth.github.io
<!DOCTYPE html>
<html>
<javascript>
<script type="Venice.javascript" src="script.js"></script>
	<head><link href="venice.css" rel="stylesheet">
	<meta charset="UTF-8">
	<body>
		<h1>VISIT VENICE ITALY!</h1>
		<div class="tab">
  <a href="javascript:void(0)" class="tablinks" onclick="openCity(event, 'Hotels')">Hotels</a>
  <a href="javascript:void(0)" class="tablinks" onclick="openCity(event, 'Things To Do')">Things To Do</a>
  <a href="javascript:void(0)" class="tablinks" onclick="openCity(event, 'Culture')">Culture</a>
  <a href="javascript:void(0)" class="tablinks" onclick="openCity(event, 'Fun Facts')">Fun Facts</a>
</div>

<div id="Hotels" class="tabcontent">
  <h3>Hotels</h3>
  <p>The best hotel for the best views in Venice is the Hotel Londra Palace. It's a four star hotel and features a beautiful view of the ocean and has over 53 rooms, each one different. In additon to the beautiful views and the glorious reburishment, visitors can enjoy the following amenities:
  <br>
  Wifi
  <br>
  Sky Tv
  <br>
  Resturant
  <br>
  Picnic: on the roof top exclusive to the hotel. It offers a 360 degree view of the city
  <br>
  Mini bar
  <br>
  A marble bathroom 
  <br>
  Walk in showers
  <br>
  Bath robes
  <br>
  The prices for a single room begin at 252 euros and extend to 600 euros


  </p>
  <img src="http://www.commdiginews.com/wp-content/uploads/2016/01/Londra-sm0321.jpg">
  <img src="https://exp.cdn-hotels.com/hotels/1000000/20000/14100/14098/77ec3cdc_z.jpg">

</div>

<div id="Things To Do" class="tabcontent">
  <h3>Things To Do</h3>
  <p>In Venice you can travel on a gondola, take a wine tour, and explore new types of fish.
  <br>
  The Doges Palace is one of the most beautiful architectual goth pieces in the world. It used to host the Venitian Government.
  <br>
  <img src="https://www.venetoinside.com/files/images/tours/veneto/palazzo-ducale-privato/palazzoducaleinter.jpg">  
  </p>
  <img src="http://www.holidayextras.co.uk/images/holidayextras-blog/grandcanal-venice-gondola.jpg">
  <img src="http://www.dchamberlinarchitect.com/g-travel-italy-venezia-venice-mercato%20rialto-fish-2013-08-27%20(34a).jpg">
</div>

<div id="Culture" class="tabcontent">
  <h3>Culture</h3>
  <p>Venice is known for.</p>
  <script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}
</script>
</div>
<img src="http://fla.fg-a.com/flags/italy-animated-flag-2.gif">
</body>
