# Astronet Tutorial

A setup guide and tutorial for Google's Tensorflow Astronet models

## Install Python

If you are using a Mac or Linux computer, you probably already have it. Open the terminal and type

    python 
  
For windows, you'll have to download and install from [here](https://www.python.org/downloads/windows/) 

## Install a Virtual Environment

    pip install virtualenv
    
## Create a Virtual Environment

    virtualenv exoplanet
    
On Windows

    exoplanet\scripts\activate
    
On Mac

    source exoplanet/bin/activate
    
## Install dependencies

You can pip install all the packages listed as required in the Astronet page, or just use my requirements.txt file

    pip install -r requirements.txt
    
Boom, everything is installed.

## Getting the CSV File Data

The column headings part is confusing unless ya'll know what you're doing, so here is the columns you are after.

1. kepid
2. tce_plnt_num = Planet Number
3. tce_period = Orbital Period
4. tce_time0bk = Transit Epoch [BKJD]
5. tce_duration = Transit Duraction [hrs]
6. av_training_set = Autovetter Training Set Label

I downbloaded the csv

## Running the Shell Script to Get the Kepler Data

You'll have no issues on Mac or Linux, but the script uses WGET, so on Windows you'll need to install this. Instructions below. 

1. 
