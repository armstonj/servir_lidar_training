# SERVIR Lidar Training

## Overview
These presentations and R Notebooks were developed to:

1.  Teach basic principles of lidar remote sensing, with a focus on airborne laser scanning (ALS)
2.  Outline important considerations in using airborne laser scanning (ALS) data for forest biomass surveys
3.  Demonstrate how these considerations should factor into the design and implementation of data processing workflows
4.  Introduce upcoming spaceborne lidar mission data products and their potential applications

This [flow diagram](https://umdgedi.bitbucket.io/servir_lidar_training/exercises_overview.html "Exercises Overview") provides an overview of the workflow and associated R Notebook exercises.


## Presentations
The presentation are intended to provide background and examples for each of the exercises.

| Description | Presentation | Exercises |
| --------|---------|-------|
| Session 1A: Lidar principles | [Google Slides](https://docs.google.com/presentation/d/1yy-OxWjzvVVEBglWnc2i4wdu8DYCM0ZPsR_ZOeJWlw0/edit?usp=sharing) | |
| Session 1B: Lidar applications | [Google Slides](https://docs.google.com/presentation/d/1ve9mjM_UHAIoArte6VqbglH_7gIqHx-6xwqnixi_M_A/edit?usp=sharing) | | 
| Session 2: ALS processing workflows | [Google Slides](https://docs.google.com/presentation/d/1ezvvd8FtbHEZnI1Spqzd-PO4I9AJC80L-ST6jL86kVk/edit?usp=sharing) | Exercises 2A & 2B |
| Session 3: In situ biomass estimation | [Google Slides](https://docs.google.com/presentation/d/1fZmtObx2z8VFso9yhEZaE7T3LqCfJMQqvHMRoUP0pgU/edit?usp=sharing) | Exercise 3 |
| Session 4: Empirical biomass modelling | [Google Slides](https://docs.google.com/presentation/d/1ejjRXIN8SE9GIF2ete5L5VUXjfYwUmg0kNkDwN5yqDY/edit?usp=sharing) | Exercises 4 & 5 |
| Session 6: Spaceborne lidar examples | [Google Slides](https://docs.google.com/presentation/d/1Cgc65cLTRB5ZoyDKoX78rdKbFrMwclhYOkUCmQpTdYw/edit?usp=sharing) | |


## R Notebooks
The exercises are provided in HTML and R Notebook format. Exercises 2A and 2B can be used with both the Kenya and Ghana pilot area ALS datasets, but users need to following instructions with the notebook to change paths where applicable.

| Description | R Notebook | Source Code |
| --------|---------|-------|
| Exercise 2A: QA/QC and manipulation of ALS point cloud files| [R Notebook (HTML)](https://umdgedi.bitbucket.io/servir_lidar_training/Exercise_2a.nb.html) | [R Markdown (Rmd)](https://bitbucket.org/umdgedi/servir_lidar_training/src/default/notebooks_r/Exercise_2a.Rmd) |
| Exercise 2B: ALS point clouds to basic canopy image products| [R Notebook (HTML)](https://umdgedi.bitbucket.io/servir_lidar_training/Exercise_2b.nb.html) | [R Markdown (Rmd)](https://bitbucket.org/umdgedi/servir_lidar_training/src/default/notebooks_r/Exercise_2b.Rmd) |
| Exercise 3: Processing tree survey data to aboveground biomass | [R Notebook (HTML)](https://umdgedi.bitbucket.io/servir_lidar_training/Exercise_3.nb.html) | [R Markdown (Rmd)](https://bitbucket.org/umdgedi/servir_lidar_training/src/default/notebooks_r/Exercise_3.Rmd) |
| Exercise 4: Aboveground biomass modelling from ALS data | [R Notebook (HTML)](https://umdgedi.bitbucket.io/servir_lidar_training/Exercise_4.nb.html) | [R Markdown (Rmd)](https://bitbucket.org/umdgedi/servir_lidar_training/src/default/notebooks_r/Exercise_4.Rmd) |
| Exercise 5: Generating aboveground biomass maps | [R Notebook (HTML)](https://umdgedi.bitbucket.io/servir_lidar_training/Exercise_5.nb.html) | [R Markdown (Rmd)](https://bitbucket.org/umdgedi/servir_lidar_training/src/default/notebooks_r/Exercise_5.Rmd) |


## Datasets
See the table below to identify which files need to be downloaded and then unzipped to your working directory for each exercise.

| File | Exercises | Description |
| --------|---------|-------|
| [ghana_alsfiles_metadata.zip](https://drive.google.com/a/umd.edu/file/d/1fbH8oFVVym_cR0Gv87xssF4AgnwwEg68/view?usp=sharing) | Exercises 2A & 2B (Ghana) | ALS files and metadata provided by the Ghana Forestry Commission |
| [127500_9992500.las](https://drive.google.com/a/umd.edu/file/d/1UruCKWyHQC27JMonon2RBdLMcnEUVG9K/view?usp=sharing) | Exercises 2A & 2B (Kenya) | Example 2.5 x 2.5 km LAS tile provided by RCMRD in Kenya | 
| [gabon_field_treedata.zip](https://drive.google.com/a/umd.edu/file/d/1g2hJjwSQMs0lHyPdwbNXdid1LOiAuC5g/view?usp=sharing) | Exercise 3 | Tree level plot inventory data from AfriSAR campaign in Gabon  |
| [afrisar_trainingdata_servir.csv](https://drive.google.com/a/umd.edu/file/d/1dW5aLyhHqrwbDZS3y5Sl3NZnCBbZdaIG/view?usp=sharing) | Exercise 4 | Plot level plot inventory data from AfriSAR campaign in Gabon |
| [gabon_biomass_models.zip](https://drive.google.com/a/umd.edu/file/d/1fosa1cmNJO5wfbu-yZJJuMY_97V_ON2D/view?usp=sharing) | Exercise 5 | R model object files output from Exercise 4 |
| [lvis_gabon_image_files.zip](https://drive.google.com/a/umd.edu/file/d/1fdsDCAsXeKkaer4YJvctNnSeFT5fwjYP/view?usp=sharing) | Exercise 5 | Tiled LVIS canopy height and cover image data products |


## Contacts
John Armston (armston@umd.edu)
Laura Duncanson (lduncans@umd.edu)
