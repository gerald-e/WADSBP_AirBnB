## Project Write a data science blog post


1. Installations
2. Project Motivation
3. Questions answered
4. Method and Results
3. File Descriptions
4. Used Libraries
5. Licensing, Authors, Acknowledgements, etc.

## Installations


## Project Motivation

Wie kann mir AirBnB bei meiner nächsten Wohnung passend zu meinem neuen Job helfen? Ich will mir es sparen in der Gegend rum zu fahren (Zeit und Geld) --> Es soll für den ersten Eindruck helfen. 

## Questions answered

Wo kann meine Tochter in Berlin am besten Leben. Dazu habe ich mir folgende Fragen gestellt:

What is the booking load?
How is the district scoring?
What are the revenues of the district?
Show me the best place to live

The article detailing the key findings of this project can be found [here](https://https://medium.com/p/e0a70f3534ac/).

## Method and Results

The project followed the CRISP-DM method of data exploration's six steps of:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation, design and show the results
6. Deployment

The developed code  for the analysis can he found in the [notebook](https://github.com/gerald-e/WADSBP_AirBnB).

To read the blog post associated with the article, you can go [here](https://medium.com/p/e0a70f3534ac/).


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
* scipy
* seaborn
* sklearn
* Bokeh

To run the section of the code involving Bokeh, you need to get a Geocoding API from google [here](https://developers.google.com/maps/documentation/geocoding/get-api-key)


## Dependencies

Each directory has a `requirements.txt` describing the minimal dependencies required to run the notebooks in that directory.

### pip

To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.


## Licensing, Authors, Acknowledgements, etc.

The data used in this project are the Berlin Airbnb Open Data from InsideAirBnB. They can be downloaded from this [link](http://insideairbnb.com/about.html)
