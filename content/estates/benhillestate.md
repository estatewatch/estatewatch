---
name: Benhill estate 
borough: sutton
tags: sutton
location: '[51.3673,-0.1901]'
landlord: Sutton Council
developer:
itla: Communities First
total: 429
ballot: Required
planning: Pending
---
{% image "src/images/bhs5.jpg", "benhill estate" %}

429 homes have been earmarked for potential development on Sutton's Benhill estate.

The Benhill estate comprising 429 homes near Sutton High Street, is one of seven estates listed in [Sutton's Local Plan (2018)](https://drive.google.com/file/d/1MdX6GlaHDoBdG6CTsvjFaIuPtIa9id5O/view) for potential redevelopment:

{% image "src/images/suttonplan.png", "alt text" %}

Sutton Council's website has a [dedicated website](https://www.sutton.gov.uk/info/200502/housing_advice_and_options/1781/benhill_estate_regeneration/3) for the Benhill estate regeneration, which it claims is in consultation stage and that no decision on the estate's future has yet been taken. It provides details of the rehousing commitment to tenants and leaseholders as well as information on forthcoming consultation events.

---

<!------------THE CODE BELOW RENDERS THE MAP - DO NOT EDIT! ---------------------------->

<div id="map" style="width: 100%; height: 400px;"></div>

<script>
  var map = L.map('map').setView({{ location }}, 13);
  L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
  maxZoom: 19,
attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
}).addTo(map);
var circle = L.circle({{ location }}, {
    color: 'red',
    fillColor: '#f03',
    fillOpacity: 0.5,
    radius: 500
}).addTo(map);
</script>

---

{% image "src/images/benhill9.jpg", "benhill estate" %}
{% image "src/images/bhs2.jpg", "benhill estate" %}
{% image "src/images/bhs3.jpg", "benhill estate" %}
{% image "src/images/benhillaerial.png", "benhill estate" %}