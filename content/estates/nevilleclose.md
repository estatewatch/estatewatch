---
name: Neville Close estate 
borough: ealing
tags: ealing
location: '[51.505661,-0.266707]'
landlord: Ealing Council
developer:
itla:
total: 50
ballot: 
planning: 
architect: 
---
{% image "src/images/nevilleclose.png", "neville close estate" %}

Circa 50 homes on the Neville Close estate have been earmarked for demolition in Ealing's [2024 Local Plan](https://www.ealing.gov.uk/download/downloads/id/19587/appendix_e_-_results.pdf).

{% image "src/images/nevilleclosesite.png", "neville close site allocation" %}

The Local Plan's site allocation states that _"the site is being actively marketed for development or enquiries have been received from a developer."_

It is not known if residents have been made aware of the proposals.


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