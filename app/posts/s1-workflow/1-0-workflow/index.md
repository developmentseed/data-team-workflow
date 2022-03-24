---
title: General workflow
date: 2012-08-20
layout: post.html
---

Development Seed's Data team has a structured and efficient workflow that involves the necessary processes and activities to generate a high-quality training dataset, and this helps them speed up the annotation process.

<figure class="align-center">
 <img src="/assets/images/data_team_workflow.jpg"/>
 <figcaption>Data team workflow</figcaption>
</figure>
 
Once the Data team knows the requirements of the customer and has access to the data input, they start the development of the project based on their workflow that contains three main processes: data exploration & workflow setup, annotation process, and output data process. In each of these phases, different activities are developed until the training data is obtained.
 
During all of these processes, the Data team is in constant communication with the customer to ensure that their requirements are met and provide feedback on the annotated classes to ensure they are suitable for machine learning models.
 
**Data input**
 
Usually clients come with their data to be processed, in some cases clients want to use public data on which the Data team has extensive experience in handling different data formats, such as vector data, street view images, raster data and map layers.
 
## Data exploration & workflow process
 
This process involves two important activities: data exploration and the engineering process.
 
**Data exploration:**
In this activity, the Data team gets trained and becomes familiar with the classes to be annotated, the Data team performs an exploration of the classes of interest to recognize and document them, and then they set up an efficient workflow that will align with the required annotation type and the annotation tool.
 
**Engineering process:**
Some projects may require annotation tool customization according to the inputs data, data team has vast experiences on tool customization, it helps to increase the annotation speed, but in some cases it is required only a data transformation on which the data team writes scripts to make the data conversion, in order to use as input in the annotation tools.
 
## Data annotation process
 
As soon as the Data team has the data input ready to use it in the annotation tool and a well-documented annotation workflow, the Data team performs the data annotation or mapping. The below list show the different annotation types that data team works:
 
- [Image Classification](/../annotation-type/image-classification/)
- [Object detection](/../annotation-type/object-detection/)
- [Segmentation](/../annotation-type/segmentation/)
- [Mapping](/../mapping/mapping/)
 
## Delivering data output process
 
Once the data annotation is completed, some last activities is required:
 
- Delivering data output in the format the client requires, sometimes it may require data format conversion and the Data team needs to write a script to convert the data. Also upload the data to the client repositories.
- Stats generation about the data annotation, example How many classes have been created in the whole dataset.
- Project feedback , In order to generate trust between client and Data team, providing feedback will be great for both ends, about what went well, what we could do better for future projects.
