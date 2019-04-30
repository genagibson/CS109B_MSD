# CS109B_MSD: Million song dataset project

Milestone 2 submitted!

## Tasks

* Rahul: Looking into Billboard data and user plays as possible better target variables. Also looking at baseline model with data in the basic dataset.
* Vladimir: Looking at song/track audio features; will look at removing mislabeled tracks; need to have an outline of doing model stacking
* Oyvind: Working on user taste profiles, and how these relate to the songs. Exploring the tag data (e.g. artist name, artist tags) to see how these can be used in the model
* Gena: Extracting the numerical data in arrays (segment pitches, segment timbre) and working out how to feed them into a model. Emailed TF to ask if changing target variable is OK.  

## To do list / ideas

* Final report due Sunday 12th May 


## Folder guide

* MSongsDB_code contains the code provided by Columbia to extract the hdf5 files. Some code has been edited to work in python 3 since the original files were written in python 2

* Notebooks is for our working code

* Reports contains project milestone deliverables


## Updates
* New notebook is created with various classical models comparison. The best accuracy is brough by Randomforest around 79%. The details can be found in the notebook 'ML_Model_v1.ipynb' under notebooks/Model/ML_Model_v1.ipynb

