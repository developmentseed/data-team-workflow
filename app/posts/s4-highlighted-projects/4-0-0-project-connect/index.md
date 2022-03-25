---
title: Project connect
date: 2012-08-23
layout: post.html
---
UNICEF Innovation Office is in charge to map every school in Kenya, Rwanda, Sierra Leone, Niger, Honduras, Ghana, Kazakhstan, and Uzbekistan, applying scalable machine learning over high-resolution satellite imagery, with the aim of accelerating connectivity, online learning and other initiatives for children and their communities and driving economic stimulus under UNICEF's GIGA mission, particularly in low-income countries. Read more of the [Project Connect technical report](http://devseed.com/project-connect-docs/).

Development Seed's Data team support this project on the training data creation and the ML inference validation.

### Training data creation

Development Seed's Data team generated a high-quality training dataset, for machine learning models, using as data sources; schools provided by UNICEF and schools data from OpenStreetMap from 9 countries, which were: Rwanda, Sierra Leone, Niger, Chad, Sudan, Mali, Honduras, Kazakhstan, and Kenya.

Finally, the Data team validated around **120k schools points**, adding one of these tags: "dc_has_pattern_school=yes", "dc_has_pattern_school=unrecognized", "dc_has_pattern_school=no"; according the school patterns recognized in each of them.

### Post inference validation

Development Seed's Data team performed a validation of the ML inferences from 8 countries (Kazakhstan, Kenya, Rwanda, Niger, Honduras, Uzbekistan, Sierra Leone, and Ghana), validating more than **113k schools tiles**.

<figure class="align-center">
  <img src="/assets/images/pc_map_visualization.gif"/>
  <figcaption>This gif shows the comparison between the schools validated for training data and the results from ML outputs validation for Kenya. You can also see more about the <a href="http://devseed.com/project-connect-visualizations/">schools map visualizations</a> for the rest of countries.</figcaption>
</figure>
