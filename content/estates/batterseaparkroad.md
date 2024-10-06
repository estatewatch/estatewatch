---
name: Battersea Park Road estate 
borough: wandsworth
tags: wandsworth
location: '[51.478880,-0.142430]'
landlord: 
developer: 
itla:
total: 100
ballot:
planning: 
---
{% image "src/images/batterseaparkroad.png", "battersea park road" %}

Circa 100 homes have been earmarked for redevelopment in Wandsworth's 2023 [Local Plan](https://www.wandsworth.gov.uk/media/large/adopted_local_plan.pdf)

The blocks situated between Battersea Park road, Thessaly road and Stewarts road have been identified as suitable for potential redevelopment with tall buildings up to 13 storeys.

{% image "src/images/batterseaparkroadsite.png", "battersea park road" %}

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