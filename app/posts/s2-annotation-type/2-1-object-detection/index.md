---
title: Object detection
date: 2012-08-20
layout: post.html
---

Machine learning Object detection is awesome and focuses on detecting certains objects on images, it’s utilized in many diverse areas: Housing infrastructure, facial detection, self-driving cars, crop field detections, etc.

Development Seed data-team has a wide experience working in this field, and for many years the dream has been building a powerful workflow that allows them to produce high quality data sets in a short time.

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

The list below of shows the tools that data-team use for image object detection work:

![image](https://devseed.com/data-team-workflow/assets/images/object-detection.png)

## CVAT

Computer Vision Annotation Tool (CVAT) is a free, open source, web-based image and video annotation tool. This tool is easily setup the CVAT server.

![](https://paper-attachments.dropbox.com/s_230DC06EACF3ACA9F9E356E4840E7091EA3153BB2E07CA5FA7F773EE60638E3E_1643658400175_chips_ahoy_image_classification.gif)

## Java OpenStreetMap editor

Java OpenStreetMap editor, known as JOSM is an open source tool. The JOSM tool works with map tiles. JOSM allows drawing polygons easily in large areas and moving around the map-tiles. JOSM works together with [osm-seed](https://github.com/developmentseed/osm-seed). a backed tools for storing the version of each polygon.

**FALTA IMAGEN DE JOSM**

## Data-team's Object Detection Projects

- [Project-connect - School object detection](/highlighted-projects/project-connect/)
