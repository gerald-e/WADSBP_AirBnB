## Project Write a data science blog post

1. Project Motivation
2. Questions answered
3. Method and Results
4. File Descriptions
5. Used Libraries
6. Installations and Dependencies
7. Licensing, Authors, Acknowledgements, etc.

## Project Motivation

How can AirBnB help me with a longer term home search and how can I save a lot of time? This analysis should help me with the search to a first impression.

## Questions answered

In order to keep the effort to find a flat as low as possible I asked myself the following questions:

What is the booking load?
How is the district scoring?
What are the revenues of the district?
Where can I find the best place to live?

The article detailing the key findings of this project can be found [here](https://medium.com/@geraldfranzkrieg/berlin-and-airbnb-a-deep-look-into-this-love-e0a70f3534ac?sk=ded53906389538ddcbd2a54f165deb34).

## Method and Results

The project followed the CRISP-DM method of data exploration's six steps of:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation, design and show the results
6. Deployment

The developed code  for the analysis can he found in the [notebook](https://github.com/gerald-e/WADSBP_AirBnB/blob/master/AirBnB%20accomondation.ipynb).


## File Descriptions

* `AirBnB accomondation.ipynb` contains the Python notebook containing all steps and further explanation for this analysis
* `./figure/*.jpg` are the outputs from all jpegs
* `./figure/*.html` are the results from HTML GeoInformation
* `./data/*` are all nesaccery data for this analysis
* `Readme.md` this file

## Used Libraries

The following libraries are required to run the notebook:

* matplotlib
* numpy
* pandas
* seaborn
* sklearn
* Bokeh

To run the section of the code involving Bokeh, you need to get a Geocoding API from google [here](https://developers.google.com/maps/documentation/geocoding/get-api-key)


## Installations and Dependencies

Each directory has a `requirements.txt` describing the minimal dependencies required to run the notebooks in that directory.

### Installations via pip

To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.


## Licensing, Authors, Acknowledgements, etc.

The data used in this project are the Berlin Airbnb Open Data from InsideAirBnB. They can be downloaded from this [link](http://insideairbnb.com/about.html)
