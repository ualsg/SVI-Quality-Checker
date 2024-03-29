# Street View Imagery Quality Checker

## Introduction
It is crucial to understand the quality of a street view imagery (SVI) dataset to assess its ’fitness for purpose’. In this repository, we present: (1) a Jupyter notebook to quickly assess the quality of a SVI dataset by **9 quality elements**, each at its relevant **hierarchical levels** - image, street, or grid; (2) a sample dataset for running the notebook.

### Quality elements
A total of 9 quality elements are evaluated in the notebook with their spatial variations visualised:
* Spatial coverage
* Spatial continuity
* Count
* Age of the most recent coverage
* Age of the first available coverage
* Number of years covered
* Number of months covered
* Time elapsed between coverage
* Image blurriness

### Sample dataset
For demonstration, we provide a set of Mapillary SVI data from a 2 km x 2 km area in Kowloon, Hong Kong for running the notebook. This includes:
* A metadata file, obtained from the [Mapillary API](https://www.mapillary.com/developer/api-documentation)
* A zip file of sample images, obtained from [Mapillary](https://www.mapillary.com/)

Apart from the SVI data, we also provide a raster file that enables the grid-based analysis, obtained from [WorldPop](https://www.worldpop.org/).

All data in the sample dataset was obtained under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## Expected outputs

The expected output for each quality element, if the sample dataset is used:

1. Spatial coverage
<div align=left>
<img src="expected_outputs/spatial-coverage.png" width="700">
</div>

2. Spatial continuity
<div align=left>
<img src="expected_outputs/spatial-continuity.png" width="350">
</div>

3. Count
<div align=left>
<img src="expected_outputs/count.png" width="700">
</div>

4. Age of the most recent coverage
<div align=left>
<img src="expected_outputs/most-recent.png" width="700">
</div>

5. Age of the first available coverage
<div align=left>
<img src="expected_outputs/first-avail.png" width="700">
</div>

6. Number of years covered
<div align=left>
<img src="expected_outputs/num-years.png" width="700">
</div>

7. Number of months covered
<div align=left>
<img src="expected_outputs/num-months.png" width="700">
</div>

8. Time elapsed between coverage
<div align=left>
<img src="expected_outputs/time-elapsed.png" width="700">
</div>

9. Image blurriness
<div align=left>
<img src="expected_outputs/blurriness.png" width="350px">
</div>


## Access
The sample dataset can be downloaded from [Google drive](https://drive.google.com/file/d/1UtAKOO5cgtqEQ7e4T4RiFkETmnLKO4El/view?usp=sharing).

## Reference, citation, and documentation

A [paper](https://doi.org/10.1016/j.jag.2022.103094) about the work was published in the _International Journal of Applied Earth Observation and Geoinformation_ and it is available open access.

If you use this work in a scientific context, please cite this article.

Hou Y, Biljecki F (2022): A comprehensive framework for evaluating the quality of street view imagery. International Journal of Applied Earth Observation and Geoinformation, 115: 103094. doi:10.1016/j.jag.2022.103094

```
@article{2022_jag_svi_quality, 
  year = {2022}, 
  title = {{A comprehensive framework for evaluating the quality of street view imagery}}, 
  author = {Hou, Yujun and Biljecki, Filip}, 
  journal = {International Journal of Applied Earth Observation and Geoinformation}, 
  doi = {10.1016/j.jag.2022.103094}, 
  pages = {103094}, 
  volume = {115}
}
```

## License
This dataset is released under the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

## Contact
Feel free to contact [Yujun Hou](https://ual.sg/authors/yujun/) or [Filip Biljecki](https://ual.sg/authors/filip/) should you have any questions.
For more information, please visit [Urban Analytics Lab](https://ual.sg/), National University of Singapore.

## Acknowledgements
We appreciate the valuable contributions of the VGI community.

We thank our colleagues at the NUS Urban Analytics Lab for the discussions.

This research is part of the project Large-scale 3D Geospatial Data for Urban Analytics, which is supported by the National University of Singapore under the Start Up Grant R-295-000-171-133.
