---
title: Turn lanes mapping project
date: 2012-08-23
layout: post.html
---

One of the big projects related to navigation and guidance in which the Data team participated was the turn lanes mapping in more than [30 cities in the US](https://github.com/mapbox/mapping/issues/180).
Turn-lanes provide directional information to the ongoing vehicles and the lane information to be chosen for the vehicles changing their direction. So turn lane information is crucial for providing great turn-by-turn guidance in navigation applications.

<figure class="align-center">
  <img src="/assets/images/mapping_4.jpg"/>
  <figcaption>Turn lanes classes.</figcaption>
</figure>

In order to improve workflow and speed up the mapping process, the Data team developed plugins such as the [knife tool](https://wiki.openstreetmap.org/wiki/JOSM/Plugins/Knife-tool), for splitting ways and [turn lanes](https://github.com/JOSM/turnlanes-tagging/blob/master/README.md) tagging.

It is so in [San Francisco, Washington DC, and Los Angeles](https://github.com/mapbox/mapping/issues/153), <b>56,686 turn lanes</b> were added faster and easier.

<table class="table">
  <thead>
    <tr>
      <th scope="col">City</th>    
      <th scope="col">Area (km²)</th>     
      <th scope="col">Total number of turn lanes</th>
      <th scope="col">Turn lane density (per km²)</th>
      <th scope="col">Porcentage of total turn lanes added by the Data team</th>
      <th scope="col">Turn lanes added per hour</th>      
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>San Francisco</td>
      <td>278.66</td>
      <td>1,780</td>
      <td>6.39</td>
      <td>51.97%</td>
      <td>12.33</td>      
    </tr>
    <tr>
      <td>Washington DC</td>
      <td>206.78</td>
      <td>745</td>
      <td>3.6</td>
      <td>81.88%</td>
      <td>114</td>         
    </tr>
    <tr>
      <td>Los Angeles</td>
      <td>7,534.92</td>
      <td>54, 161</td>
      <td>7.19</td>
      <td>94.87%</td>
      <td>321.15</td>         
    </tr>    
  </tbody>
</table>
</br>

In this way, the Data team collaborated with the community to expand the turn lane coverage and to improve the navigation data in [OpenStreetMap](https://www.openstreetmap.org/).
