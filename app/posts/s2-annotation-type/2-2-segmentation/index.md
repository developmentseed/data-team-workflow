---
title: Segmentation
date: 2012-08-20
layout: post.html
---

Currently generating machine learning segmentation training data is challenging work, Development Seed engineers and the Data team have been testing different tools for the use cases, they found some useful tools, such as JOSM and Photopea, so the Data team are including these tools in its workflows, and they currently getting good results in turns of time and quality.

<figure class="align-center">
  <img src="/assets/images/flowchart_segmentation.png"/>
  <figcaption>Input, tools, and output diagram for segmentation.</figcaption>
</figure>

## Data team's segmentation tools

The list below shows the tools that the Data team uses for segmentation work.

### Photopea
[Photopea](https://www.photopea.com/) is a web-based photo & graphics editor which can work with raster and vector graphics, it has a magic wand option, which helps increase speed labeling work.

<figure class="align-center">
  <img src="/assets/images/segmentation_tool_photopea.gif"/>
  <figcaption>The gif shows the annotation of field farms, the annotation is faster using the magic wand option.</figcaption>
</figure>


### Java OpenStreetMap editor

Java OpenStreetMap editor, known as [JOSM](https://josm.openstreetmap.de/) is an open-source tool. The JOSM tool works with map tiles. JOSM allows drawing polygons easily in large areas and moving around the map tiles. JOSM works together with [osm-seed](https://github.com/developmentseed/osm-seed) a backed tool for storing the version of each polygon. JOSM tool is useful when is needed to annotate several classes.

<figure class="align-center">
  <img src="/assets/images/segmentation_tool_josm.gif"/>
  <figcaption>The gif shows the annotation of 4 different classes as grass/shrub, other impervious (service roads, parking lots), tree canopy, and building.</figcaption>
</figure>

## Data team's segmentation projects

- [Training dataset for PEARL](/highlighted-projects/training-dataset-for-pearl/)
