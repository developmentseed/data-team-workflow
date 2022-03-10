---
title: Classification projects
date: 2012-08-23
layout: post.html
---

## Project connect

UNICEF Innovation Office to map every school in Kenya, Rwanda, Sierra Leone, Niger, Honduras, Ghana, Kazakhstan, and Uzbekistan, applying scalable machine learning over high-resolution satellite imagery, with the aim of accelerating connectivity, online learning and other initiatives for children and their communities and driving economic stimulus under UNICEF's GIGA mission, particularly in low-income countries. You can always read more of the [Project Connect technical report](http://devseed.com/project-connect-docs/).
DevelopmentSeed data team generated a high-quality training dataset for machine learning models using as data source; schools provided by UNICEF and schools data from OpenStreetMap.
In addition to the training data generation, the data team performed a validation of the ML outputs.

### Training data creation stats

### Post inference validation:

Among all these countries, the data team validated around 120k schools points for generating the training dataset, and more than 113k schools from the ML outputs.
The below gift shows the comparison between the schools validated for training data and the results from ML outputs validation for Kenya. You can also see more about the [schools map visualizations](http://devseed.com/project-connect-visualizations/) for the rest of countries.

<figure class="align-center">
  <img src="/assets/images/classification_kenya.gif"/>
  <figcaption>Map viewer for Kenya </figcaption>
</figure>

### Tools

To develop this project, the data team use different tools, resources and open source data from OpenStreetmap, for the training data generation and the ML ouputs validation.

#### Training data generation:

In this phase of work, data team combined different tools such us; JOSM, the edition tool which was customized to move and add tags to the school point in the map trough shortcuts; Osm-seed, OpenStreetMap software backend where we store the data; Tasking mannager, to split tasks between the different mappers and Mapbox studio to create some styles that was load in the JOSM editor to do more accurate labeling.
With all these set of tools data team was able to validate 209 schools per hour adding a tag to each school point to classify between those that have clear schools patterns (dc_has_pattern_school=yes), those had no clear school patterns (dc_has_pattern_school=unrecognized) and those schools that were mislocated like schools in the middle of desert or dense forest (dc_has_pattern_school=no).

<figure class="align-center">
  <img src="/assets/images/classification_tool_1.gif"/>
</figure>

After the data team finished the validation of the schools dataset, the Data team generated the supertiles from the tiles of the category “school” and "not-school".

<figure class="align-center">
  <img src="/assets/images/classification_tool_2.jpeg"/>
</figure>

## Machine Learning ouputs validation

In this phase of work, data team validated the the inference result for all countries using CHIP-AHOY, a tool developed by DevelopmentSeed and that allow us to validate machine learning chips. With this tool, data team was able to validate <b> 1000 tiles per hour</b>, labeling them as <b>“yes”</b>, <b>“no”</b> or <b>“unrecognized</b> the schools detected by Machine Learning.

<figure class="align-center">
  <img src="/assets/images/classification_chips.gif"/>
  <figcaption>Chips-ahoy tool</figcaption>
</figure>
