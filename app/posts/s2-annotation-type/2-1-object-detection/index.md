---
title: Object detection
date: 2012-08-20
layout: post.html
---

Machine learning object detection is awesome and focuses on detecting certain objects on images, so it’s utilized in diverse areas, for instance: housing infrastructure, facial detection, self-driving cars, crop field detections, and so on.

Development Seed's Data team has a wide experience working in this field, and for many years the dream has been to build a powerful workflow that allows them to produce high-quality data sets in a short time.

<figure class="align-center">
  <img src="/assets/images/flowchart_object_detection.png"/>
  <figcaption>Input, tools, and output diagram for object detection.</figcaption>
</figure>

The table below indicates the Data team's average on the objects annotation.

<table class="table">
  <thead>
    <tr>
      <th scope="col">Classes per image</th>
      <th scope="col">Images per hour</th>
      <th scope="col">Min/Max image size in pixels</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>120</td>
    <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
    <tr>
      <td>2</td>
      <td>100</td>
      <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
    <tr>
      <td>3</td>
      <td>80</td>
      <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
  </tbody>
</table>
</br>

## Data team's object detection tools

The list below of shows the tools that Data team use for image object detection work.

### CVAT

Computer Vision Annotation Tool (CVAT) is a free, open-source, web-based image and video annotation tool. Is easily setup the CVAT server.

<figure class="align-center">
  <img src="/assets/images/object_detection_tool_cvat.gif"/>
  <figcaption>It shows the building detection, in this case, is necessary to draw a bbox that cover the building in order to identify to which building belongs and also the building should be classified according to its characteristic for instance: the last building is fully built, the building material is wood polished and it is residential.</figcaption>
</figure>

### Java OpenStreetMap editor

Java OpenStreetMap editor, known as JOSM is an open-source tool. The JOSM tool works with map tiles. JOSM allows drawing polygons easily in large areas and moving around the map tiles. JOSM works together with [osm-seed](https://github.com/developmentseed/osm-seed) a backed tool for storing the version of each polygon.

<figure class="align-center">
  <img src="/assets/images/object_detection_tool_josm.gif"/>
  <figcaption>The annotation for object detection is fast with JOSM, in this example, the object to annotate is the school, so the bbox needs to cover the school boundary.</figcaption>
</figure>

## Data team's object detection projects

- [Housing Passport](/highlighted-projects/housing-passport/)
