---
title: Image classification
date: 2012-08-20
layout: post.html
---

Machine Learning image classification projects are characterized by reviewing large amounts of images looking for certain patterns, for instance: school patterns, vacant lots, crop types, and so on.

The Data team along with Machine Learning engineering have built workflow and tools to review large numbers of images in an easy way.

<figure class="align-center">
  <img src="/assets/images/flowchart_image_classification.png"/>
  <figcaption>Input, tools, and output diagram for image classification.</figcaption>
</figure>

The statistics below demonstrate the efficiency of tools and the Data team at image classification.

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
      <td>1,000</td>
      <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
    <tr>
      <td>2</td>
      <td>800</td>
      <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
    <tr>
      <td>3</td>
      <td>700</td>
      <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
    <tr>
      <td>4</td>
      <td>600</td>
      <td>256x256 <strong>/</strong> 2048x2048</td>
    </tr>
  </tbody>
</table>

## Data team's image classification tools

Development Seed's Data team has built its own tools to address these types of challenges, which allow them to do quick reviews.

The list below shows the tools that the Data team uses for image classification.

### Chips-ahoy

[Chips-ahoy](https://devseed.com/chips-ahoy/) is an open-source tool, used for validating machine learning chips. This tool is useful when the tiles for validation are scattered.

<figure class="align-center">
  <img src="/assets/images/image_classification_tool_chips_ahoy.gif"/>
  <figcaption>The gif shows the school validation process where the Data team validated each of the predicted schools as either “confirmed”, “unrecognized”, and “not-school”. This tool allows the Data team to view the progress percentage of the validation process and download the data at the end of the validation process.</figcaption>
</figure>

### Relabeler

[Relabeler](https://devseed.com/relabeler/) is an open-source tool, used for validating map tiles chips. This tool is useful when the tiles for validation are together or close to each other.

<figure class="align-center">
  <img src="/assets/images/image_classification_tool_relabeler.gif"/>
  <figcaption>With this tool, the Data team validated 11 categories of POI's, such us: "hospital", "background", "university", "school", "place of worship", "government", "transportation", "commercial", "industry", "sport", and "residential". During the validation process, the Data team checked each bboxes according to the patterns of each category.</figcaption>
</figure>


### Java OpenStreetMap editor

Java OpenStreetMap editor, known as [JOSM](https://josm.openstreetmap.de/) is an open-source tool, this tool works with map tiles. JOSM allows the editions to be easier and faster with points, lines, and polygons compared with QGIS. The Data team uses JOSM together with [osm-seed](https://github.com/developmentseed/osm-seed), also during years Development Seed engineers got experience customizing JOSM for their own purposes it means according to the project necessity.

<figure class="align-center">
  <img src="/assets/images/image_classification_tool_josm.gif"/>
  <figcaption>The gif shows the school validation process where our team validated if each school point has the school patter, and according to it add the following tag: "dc_has_pattern_school=yes", "dc_has_pattern_school=unrecognized", "dc_has_pattern_school=no". JOSM also allows the Data team to move the detection point to the school boundary center of each school in order to get the accurate school tiles.</figcaption>
</figure>

## Data team's classification projects

The following list shows the projects of image classification for Machine Learning training data.

- [Project connect](/highlighted-projects/project-connect/)
