---
title: Road Safety
date: 2012-08-23
layout: post.html
---

This project was to support the World Bank’s Road Safety program to use computer vision and street view images to detect road features for road safety audits and assesments.

Development Seed's Data team supported on the workflow design and the imagery labeling. For this, the Data team performed a discovery process to review and find all the useful attributes to evaluate the road safety and those that were possible to recognize and label in the street level images. The road safety priority classes that were annotated is detailed in our [guidelines for labeling road safety classes](http://devseed.com/ml-road-safety-labeling/).

As images source, the Data team used Mapillary to obtain street view images from the routes provided by World Bank. These routes where from different countries and included paved county roads, unpaved rural roads, and national roads.

**Stats:**
Among all the routes in different countries, the Data team labeled around **6k images**.

<figure class="align-center">
  <img src="/assets/images/object_detection_stats2.png"/>
   <figcaption>Stats of classes and total images labeled.</figcaption>
</figure>
