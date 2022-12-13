---
title: Mapping
date: 2012-08-20
layout: post.html
---

The Data team has mapped and edited more than 25 million objects in OpenStreetMap and created routable road networks for the biggest names in navigation, so Development Seed's Data team is among the best in the world at creating and improving map data. The Data team has extensive experience with the OSM ecosystem, software stack, and metadata standards. Something to keep in mind is that the Data team members come to Development Seed from Mapbox where they worked on several of the biggest and toughest mapping challenges.

The Data team offers data with high quality and also a good average on mapping, the average on mapping varies according to the density and complexity of the features to map, and also of the satellite imagery quality. Here there is the Data team average per each feature:

### - Building:
For mapping buildings, the Data team average varies according to the density of the buildings that are in an area. This density is classified as low, intermediate, and high.

<table class="table">
  <thead>
    <tr>
      <th scope="col"; style="width: 25%; text-align: center">Low</th>
      <th scope="col"; style="width: 25%; text-align: center">Intermediate</th>
      <th scope="col"; style="width: 25%;text-align: center">High</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img src="/assets/images/building_low_density.png"/>            
      </td>
      <td>
        <img src="/assets/images/building_intermediate_density.png"/>            
      </td>
      <td>
        <img src="/assets/images/building_high_density.png"/>            
      </td>
    </tr>
    <tr>
      <td style="text-align: justify; padding: 12px;">Where there are only a few buildings. This density type can be seen in rural areas.</td>
      <td style="text-align: justify; padding: 12px;">Where there are a lot of buildings. This density type can be seen in urban areas.</td>
      <td style="text-align: justify; padding: 12px;">Where there are a lot of buildings, in addition, the buildings are well together. This density type can be seen in urban areas.</td>
    </tr>
  </tbody>
</table>
<br></br>

The table below indicates the average mapping time of buildings per square kilometer.

<table class="table">
  <thead>
    <tr>   
      <th scope="col"; style="width: 25%">Density area</th>        
      <th scope="col"; style="width: 25%">Area</th>      
      <th scope="col"; style="width: 25%">Time (hour)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Low</td>
      <td>1km²</td>
      <td>0.67</td>
    </tr>
    <tr>    
      <td>Intermediate</td>
      <td>1km²</td>
      <td>4</td>
    </tr>
    <tr>    
      <td>High</td>
      <td>1km²</td>
      <td>10</td>
    </tr>    
  </tbody> 
</table>

### - Highway:
For mapping highways, the Data team average varies according to the density of the buildings that are in an area. This density is classified as low, intermediate, and high.

<table class="table">
  <thead>
    <tr>
      <th scope="col"; style="width: 25%; text-align: center">Low</th>
      <th scope="col"; style="width: 25%; text-align: center">Intermediate</th>
      <th scope="col"; style="width: 25%;text-align: center">High</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img src="/assets/images/highway_low_density.png"/>            
      </td>
      <td>
        <img src="/assets/images/highway_intermediate_density.png"/>            
      </td>
      <td>
        <img src="/assets/images/highway_high_density.png"/>            
      </td>
    </tr>
    <tr>
      <td style="text-align: justify; padding: 12px;">Where there are only a few highways. This density type can be seen in rural areas.</td>
      <td style="text-align: justify; padding: 12px;">Where there are a lot of highways. This density type can be seen in urban areas.</td>
      <td style="text-align: justify; padding: 12px;">Where there are a lot of highways. This density type can be seen in urban areas.</td>
    </tr>
  </tbody>
</table>
<br></br>

The table below indicates the average mapping time of highways per square kilometer.

<table class="table">
  <thead>
    <tr>   
      <th scope="col"; style="width: 25%">Density area</th>        
      <th scope="col"; style="width: 25%">Area</th>      
      <th scope="col"; style="width: 25%">Time (hour)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Low</td>
      <td>1km²</td>
      <td>0.15</td>
    </tr>
    <tr>    
      <td>Intermediate</td>
      <td>1km²</td>
      <td>0.25</td>
    </tr>
    <tr>    
      <td>High</td>
      <td>1km²</td>
      <td>0.25</td>
    </tr>    
  </tbody>  
</table>

### - Farm field:
For mapping farm fields, the Data team average varies according to the farm field shape complexity. This shape complexity is classified as low, medium, and high.

<table class="table">
  <thead>
    <tr>
      <th scope="col"; style="width: 25%; text-align: center">Low</th>
      <th scope="col"; style="width: 25%; text-align: center">Medium</th>
      <th scope="col"; style="width: 25%; text-align: center">High</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <img src="/assets/images/farm_low_complexity.png"/>            
      </td>
      <td>
        <img src="/assets/images/farm_medium_complexity.png"/>               
      </td>
      <td> 
        <img src="/assets/images/farm_high_complexity.png"/>               
      </td>
    </tr>
    <tr>
      <td style="text-align: justify; padding: 12px;">Where the farm field shape is simple.</td>
      <td style="text-align: justify; padding: 12px;">Where the farm field shape has a few edges.</td>
      <td style="text-align: justify; padding: 12px;">Where the farm field shape has complex edges.</td>
    </tr>
  </tbody>
</table>
<br></br>

The table below indicates the average mapping time of farm fields.

<table class="table">
  <thead>
    <tr>   
      <th scope="col"; style="width: 25%">Complexity</th>     
      <th scope="col"; style="width: 25%">N° farm fields</th>
      <th scope="col"; style="width: 25%">Time (hour)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Low</td>
      <td>60</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Intermediate</td>
      <td>40</td>
      <td>1</td>
    </tr>
    <tr>
      <td>High</td>
      <td>20</td>
      <td>1</td>
    </tr>    
  </tbody>
</table>

## Data team's mapping tools
The Data team, for mapping, use these tools:

- [JOSM](https://josm.openstreetmap.de/) as an editor, where the Data team can do easier and faster the editions.
- [Tasking Manager](https://github.com/hotosm/tasking-manager), for dividing the AOI into small areas in order to each mapper can select a task, and avoid conflicts.
- [OpenStreetMap](https://www.openstreetmap.org/), a collaborative project to create free and editable maps.

## Data team's mapping projects

The following list shows the mapping projects where the Data team has worked.

- [Earthquake mapping in Indonesia](/highlighted-projects/earthquake-mapping-in-indonesia/)
- [Camps mapping in Chad](/highlighted-projects/camps-mapping-in-chad/)
- [Buildings mapping in San Francisco](/highlighted-projects/buildings-mapping-in-san-francisco/)
- [Mapping and aligning road network in Taiwan](/highlighted-projects/mapping-and-aligning-road-network-in-taiwan/)
- [Los Angeles building import](/highlighted-projects/los-angeles-building-import/)
- [Turn lanes mapping project](/highlighted-projects/turn-lanes-mapping/)
- [Machine learning tower detection and mapping work](/highlighted-projects/machine-learning-tower-detection-and-mapping-work/)
- [Farm fields mapping](/highlighted-projects/farm-fields-mapping/)
- [Commercial farms mapping in Ethiopia](/highlighted-projects/commercial-farms-mapping-in-ethiopia/)
