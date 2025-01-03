---
name: Copley Close estate
borough: ealing
tags: ealing
location: '[51.520018,-0.330991]'
landlord: LB Ealing
developer:
itla:
total: 333
ballot: 
planning: 
architect: 
---
{% image "src/images/copleyclose.png", "Copley Close estate" %}

333 homes at the Copley Close estate in Hanwell have been earmarked for potential redevelopment in Ealing's [2024 Local Plan](https://www.ealing.gov.uk/download/downloads/id/19587/appendix_e_-_results.pdf).

{% image "src/images/copleyclosesite.png", "Copley close site allocation" %}

This is the southern part of the estate comprising Monmouth, Oxford, Paddington, Pembroke, Radnor, Shropshire, Somerset and Stafford Courts.

The northern part of the estate has undergone some refurbishment works and this part was also scheduled to undergo refurbishment but redevelopment has now been listed as an option in the Local Plan's site allocation.

It is not known if residents have been made aware of the designation.

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