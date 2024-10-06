---
name: Rosehill Court 
borough: sutton
tags: sutton
location: '[51.385183,-0.189415]'
landlord: Sutton Council
developer:
itla:
total: 50
ballot: Exempt
planning: Pending
---
{% image "src/images/rosehillcourt.jpg", "rosehill court" %}

50 homes are listed for potential demolition at Rosehill Court, which is part of Sutton's St. Helier estate in Carshalton.

In September 2017, it was [listed](https://moderngov.sutton.gov.uk/documents/s54307/7%20Housing%20Revenue%20Account%20Business%20Plan%20201718%20-%20204647%20-%20Appendix%20A.pdf) as 'amber' in Sutton's [stock investment review](https://moderngov.sutton.gov.uk/documents/s54306/7%20Housing%20Revenue%20Account%20Business%20Plan%20201718%20-%20204647.pdf) which requires an options appraisal on the future of the building before any continued investment in its upkeep:

{% image "src/images/rosehillamber.png", "alt text" %}

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


