# To reproduce the conda environment

**Note** the example commands used below are for Unix/Linux operating systems

``` conda env create -f environment.yml ```

The new conda enviornment will be named *yolo*.

To activate the enviorment run

``` conda activate yolo ```
or
``` source activate yolo ```

## To get the flask API running locally on your machine

First clone this repository

``` git clone https://github.com/soph-py/object_detection.git ```
Remember to update your Google api key in .env file


Once the conda environment is activated, change directories to app/

``` cd ./app ```

Then start running the Flask app (making sure you have the yolo enviorment activated and flask installed) by running the following:

``` python app.py ```

Once the Flask app is running, run the code in *main.py* to make a test post request
