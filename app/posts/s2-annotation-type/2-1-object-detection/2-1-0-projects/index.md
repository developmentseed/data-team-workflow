---
title: OD projects
date: 2012-08-23
layout: post.html
---

## Housing passport

This project was to support the World Bank’s Global Program on Resilient Housing to find vulnerable housing, that are potentially dangerous during earthquakes or other disasters, in street view images using AI. You can always read more about [Finding vulnerable housing in street view images using AI to create safer cities](http://devseed.com/blog/2019-05-08-finding-vulnerable-housing-in-street-view-images-using-ai-to-create-safer-cities).
DevelopmentSeed data team generated training data, with a large, high-quality dataset, anyone can use that to develop ML models and find vulnerable houses faster/easier. For this, data team processed the Street View images collected by the World Bank, and then labeled the building properties and building parts focused on features that are relevant when assessing a building's resiliency. More details about the annotated features can be found in our [guidelines for Housing Passport labeling](http://devseed.com/housing-passports-labeling/).

### Stats

Data team labeled dataset for 8 cities in different countries such as; Colombia, Peru, Mexico, St. Maarten island and Saint Lucia, where we achieved the annotation of around 70k images among the buildings with different properties and 4 types of building parts (window, door, garage, disaster mitigation).

<figure class="align-center">
  <img src="/assets/images/object_detection_stats1.png"/>
</figure>

### Tools

<b>CVAT</b>: For this annotation process, data team used Computer Vision Annotation Tool ([CVAT](https://github.com/openvinotoolkit/cvat)) a free, open source, web-based image and video annotation tool. We setup the CVAT server, uploaded the images to the server and then we created the tasks to divide the work between the data team members. With this tool, data team labeled 75 images per hour annotating 7 classes for buildings properties and 4 types of buildings parts.

<figure class="align-center">
  <img src="/assets/images/object_detection_tool_1.gif"/>
</figure>

## Road Safety

This project was to support the World Bank’s Road Safety program to use computer vision and street view images to detect road features for road safety audits and assesments.
Developmentseed data team supported on the workflow design and the imagery labeling. For this, data team performed a discovery process to review and find all the useful attributes to evaluate the road safety and those that were possible to recognize and label in the street level images. The road safety priority classes that were annotated is detailed in our [guidelines for labeling road safety classes](http://devseed.com/ml-road-safety-labeling/).
As images source, the data team used Mapillary to obtain street view images from the routes provided by World Bank. These routes where from different countries and included paved county roads, unpaved rural roads, and national roads.

### Stats

Data team labeled around 6k images

<figure class="align-center">
  <img src="/assets/images/object_detection_stats2.png"/>
</figure>
