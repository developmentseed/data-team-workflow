---
title: Housing passports
date: 2012-08-23
layout: post.html
---

This project was to support the World Bank’s Global Program on Resilient Housing to find vulnerable housing, that are potentially dangerous during earthquakes or other disasters, in street view images using AI. You can always read more about [Finding vulnerable housing in street view images using AI to create safer cities](http://devseed.com/blog/2019-05-08-finding-vulnerable-housing-in-street-view-images-using-ai-to-create-safer-cities).
DevelopmentSeed data team generated training data, with a large, high-quality dataset, anyone can use that to develop ML models and find vulnerable houses faster/easier. For this, data team processed the Street View images collected by the World Bank, and then labeled the building properties and building parts focused on features that are relevant when assessing a building's resiliency. More details about the annotated features can be found in our [guidelines for Housing Passport labeling](http://devseed.com/housing-passports-labeling/).

-- Stats

**Stats:**
Data team labeled dataset for 8 cities in different countries such as; Colombia, Peru, Mexico, St. Maarten island and Saint Lucia, where we achieved the annotation of around 70k images among the buildings with different properties and 4 types of building parts (window, door, garage, disaster mitigation).

<figure class="align-center">
  <img src="/assets/images/housing-passport_1.gif"/>
  <figcaption> <b>Detecting building properties in street view imagery.</b> Sample detections for building completeness (left), design (middle), and construction material (right). Notice that the models work reasonably well even with obstructions (like this bus).</figcaption>
</figure>

<figure class="align-center">
  <img src="/assets/images/housing-passport.gif"/>
  <figcaption> <b>Registering street view detections to the map</b>. The continuous stream of images often leads to several detections per structure (left). Knowing the car’s location, heading, and camera field of view, we create a geospatial line for each bounding box detection originating at the car and pointing outward (right). We assign this detected property (and confidence) to the first building polygon (blue box) intersected.</figcaption>
</figure>
