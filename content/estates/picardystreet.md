---
name: Picardy Street estate 
borough: bexley
tags: bexley
location: '[51.490741,0.150198]'
landlord:
developer:
itla:
total: 150
ballot: Required
planning: Pending
---
{% image "src/images/picardystreet.jpg", "picardy st estate" %}

Circa 150 homes on Bexley's Picardy Street estate in Belvedere have been earmarked for redevelopment in Bexley's [Local Plan](https://www.bexley.gov.uk/sites/bexley-cms/files/2019-02/BLP-Reg-18-Consultation-Paper-for-Publication-February-2019.pdf) - (site BV0006). 

The estate is relatively small, comprising around a dozen 4-storey blocks of maisonettes plus a row of semi-detached homes and is situated within close proximity of Belvedere station - and is within walking distance from the new Abbey Wood crossrail station.

A masterplan for the redevelopment of the estate is yet to be drawn up.


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
