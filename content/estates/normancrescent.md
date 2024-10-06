---
name: Norman Crescent estate 
borough: hounslow
tags: hounslow
location: '[51.481943,-0.393027]'
landlord: Hounslow Council
itla:
total: 300
ballot: Required
planning: Pending
---
{% image "src/images/nc4.jpg", "norman crescent estate" %}

Circa 300 homes are earmarked for potential demolition on Hounslow's Norman Crescent estate.

In January 2020, Hounslow's Cabinet [agreed a comprehensive review](https://democraticservices.hounslow.gov.uk/documents/s157644/CEX432%20Housing%20Estate%20Regeneration%20Programme.pdf) of its 171 council estates with a view to infill or redevelopment.

In the [Cabinet report](https://democraticservices.hounslow.gov.uk/documents/s157644/CEX432%20Housing%20Estate%20Regeneration%20Programme.pdf) it was agreed that six estates had already been identified as 'poor performing estates' and that these would be considered for early redevelopment.

The six estates are: the Brabazon estate; the Brookwood estate; Charlton House; the Convent Way estate; the Norman Crescent estate and the Oriel estate.


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


