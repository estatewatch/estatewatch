---
name: Convent Way estate
borough: hounslow
tags: hounslow
location: '[51.494632,-0.393576]'
landlord: Hounslow Council
developer:
itla:
total: 440
ballot: Approved
planning: Approved
architect: Bell Phillips
---
{% image "src/images/cv20.jpg", "Collingwood estate" %}

440 homes are earmarked for demolition on Hounslow's Convent Way estate.

In January 2020, Hounslow's Cabinet [agreed a comprehensive review](https://democraticservices.hounslow.gov.uk/documents/s157644/CEX432%20Housing%20Estate%20Regeneration%20Programme.pdf) of its 171 council estates with a view to infill or redevelopment.

In the [Cabinet report](https://democraticservices.hounslow.gov.uk/documents/s157644/CEX432%20Housing%20Estate%20Regeneration%20Programme.pdf) it was agreed that six estates had already been identified as 'poor performing estates'. 

The six estates are: the Brabazon estate; the Brookwood estate; Charlton House; the Convent Way estate; the Norman Crescent estate and the Oriel estate.

The Convent Way estate was identified as the most likely of these 'poor performing estates' that would benefit from early regeneration.

The estate was originally built in 1967. It comprises of one 12 storytower block, 16 medium rise (3 to 5 storey) blocks. In total the estate comprises 440 homes. In addition, the estate contains a health centre, community centre, and a small shopping parade.

The Council's [2020 Cabinet report](https://democraticservices.hounslow.gov.uk/documents/s157644/CEX432%20Housing%20Estate%20Regeneration%20Programme.pdf) explains that the estate was chosen after an audit showed it faced increasing bills for maintenance as well as concerns over nuisance behaviour like fly-tipping.

{% image "src/images/conventmap.png", "alt text" %}

In April 2021, Hounslow started [consulting](https://haveyoursay.hounslow.gov.uk/housing/conventfeedback/) on its [Landlord Offer](/images/Landlord_Offer_Convent_Way.pdf) to residents ahead of an expected ballot.

85% of residents subsquently voted in favour of redevelopment. It is not known how many residents turned out for the vote.

A planning application was approved in 2022 for 967 new homes of which 50% affordable rent (up to 80% market rent). All of the new homes are proposed to be constructed to Passive House standards.

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

{% image "src/images/cv11.jpg", "Collingwood estate" %}
{% image "src/images/cv13.jpg", "Collingwood estate" %}
