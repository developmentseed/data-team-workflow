---
title: General workflow
date: 2012-08-20
layout: post.html
---

Development Seed's Data team has a structured and efficient workflow that involves the necessary processes and activities to generate a high-quality training dataset, and this helps them speed up the annotation process.

<figure class="align-center">
 <img src="/assets/images/data_team_workflow_qa.jpg"/>
 <figcaption>Data team workflow</figcaption>
</figure>
 
Once the Data team knows the requirements of the customer and has access to the data input, they start the development of the project based on their workflow that contains three main processes: data exploration & workflow, data annotation, and delivering output data. In each of these processes, different activities are developed until the training data is obtained.
 
Along the processes on the workflow, communication and quality assurance process were embedded to ensure the training data aligns with the customer's expectations.
 
## Data input
 
Usually customers come with their data to be processed, in some cases customers want to use public data on which the Data team has extensive experience in handling different data formats, such as vector data, street view images, raster data and map layers.
 

 
## Delivering data output process
 
Once the data annotation is completed, some last activities is required:
 
- Delivering data output in the format the customer requires; sometimes it may require data format conversion and the Data team needs to write a script to convert the data. Also upload the data to the customer repositories.
- Stats generation about the data annotation; for example, how many classes have been created in the whole dataset.
- Project feedback; in order to generate trust between customer and the Data team, providing feedback will be great for both ends, about what went well, what we could do better for future projects.

## Quality assurance

The Data team is fully aware that data quality is directly related to the effectiveness of AI/ML models, so, ensuring data quality is of great importance. For this reason, the Data team embedded the Quality Assurance (QA) process in its workflow in such a way that it allows to guarantee a continuous improvement of the training data during the data annotation process and the delivering data output process.

Some good practices of the Data team to deliver high-quality training data are:


- Internal revision; the Data team does a revision of the first bunch of the annotated data to ensure that all the annotators are following the same perspective in the labeling and to find possible common issues in advance.
- Feedback from customers; the Data team sends one first dataset of the annotation in order to have a revision of the customers and receive feedback.

In addition to manual data validation, the Data team customizes its annotation tools for data validation and writes scripts to find issues in the data automatically, thus speeding up the QA process.

### Continuous communication

The Data team is in constant communication with the customers throughout all the processes of the workflow to ensure that their requirements are met and provide feedback on the annotated classes to ensure they are suitable for machine learning models.