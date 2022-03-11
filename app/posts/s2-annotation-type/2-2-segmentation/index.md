---
title: Segmentation
date: 2012-08-20
layout: post.html
---

Currently generating machine learning segmentation training data is challenging work, Development Seed engineers and data-team have been testing diferentes tools for the use cases, we found some useful tools. Such as JOSM and Photopea and convening them in our workflows are currently getting good results in turns of time and quality, following table shows data-team stast in segmentation work.

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
      <td>6</td>
    <td>2048x2048 <strong>/</strong>6404×4175</td>
    </tr>
    <tr>
      <td>3</td>
      <td>5</td>
      <td>2048x2048 <strong>/</strong>6404×4175</td>
    </tr>
    <tr>
      <td>6</td>
      <td>4</td>
      <td>2048x2048 <strong>/</strong>6404×4175</td>
    </tr>
  </tbody>
</table>

The list below of shows the tools that data-team use for image object detection work 👇


![image](/assets/images/segmentation.png)

## Photopea
Photopea is a web-based photo & graphics editor which can work with raster and vector graphics, it has a magic wand tools, which helps increasing speed  labeling work.

![](https://user-images.githubusercontent.com/22258697/152452065-2e7879e7-f832-4164-a553-d33ffeab1cbf.gif)


## Java OpenStreetMap editor

Java OpenStreetMap editor, known as JOSM is an open source tool. The JOSM tool works with map tiles. JOSM allows drawing polygons easily in large areas and moving around the map-tiles. JOSM works together with [osm-seed](https://github.com/developmentseed/osm-seed). a backed tools for storing the version of each polygon.

![](https://user-images.githubusercontent.com/22258697/152451882-ea8a32cb-d30d-4ce9-8b44-f865043fab5e.gif)

## Data-team's Segmentation Projects

- 
