---
name: Yeading Lane 2 estate
borough: ealing
tags: ealing
location: '[51.531224,-0.381707]'
landlord: LB Ealing
developer:
itla:
total: 150
ballot: 
planning: 
architect: 
---
{% image "src/images/yeadinglane2.png", "Yeading Lane estate" %}

Circa 150 homes at the Yeading Lane 2 estate in Northolt have been earmarked for potential redevelopment in Ealing's [2024 Local Plan](https://www.ealing.gov.uk/download/downloads/id/19587/appendix_e_-_results.pdf).

{% image "src/images/yeadinglane2site.png", "Yeading Lane site allocation" %}

It is not known if residents have been made aware of the designation. The site allocation states that it _"is a strategic site for Northolt. Although not actively being marketed, there is interest in regeneration of the site, which should come forward within 6-10 years."_

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