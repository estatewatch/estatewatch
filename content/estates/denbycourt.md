---
name: Denby Court 
borough: lambeth
tags: lambeth
location: '[51.493660,-0.115040]'
landlord: Lambeth Council
developer:
itla:
total: 42
ballot: Exempt
planning: Approved
---
42 homes have been earmarked for demolition by Lambeth Council at Denby Court in Kennington.

Lambeth proposes to demolish this former sheltered housing block, which is currently being used as temporary accommodation for families on its housing waiting list.

The site also contains a former education facility, which will also be demolished as part of the scheme. Lambeth proposes to build 144 new homes on the site of which it says 50% will be affordable, of which 70% will be 'council level rent' and 30% shared ownership.

In January 2021, residents were informed by the Council that they would be moved out imminently to temporary accommodation elsewhere. Residents are resisting the move and lobbying the Council to stay put until they are rehoused permanently in the local area. Many of them have lived in Denby Court for several years. Their plight was covered by the Guardian newspaper in [this Jan 2021 article](https://www.theguardian.com/society/2021/jan/31/dont-make-us-move-in-a-pandemic-plead-tenants-in-dire-council-housing).

In March 2022, Lambeth Council granted itself planning permission for redevelopment of Denby Court. 

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

{% image "src/images/denby2.png", "Dell court" %}
{% image "src/images/denby3.png", "Dell court" %}
{% image "src/images/denby4.png", "Dell court" %}