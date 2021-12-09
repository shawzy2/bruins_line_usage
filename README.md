# Top Line Usage - Bruins Homework
This project aims to answer the prompt: Which teams give the most ice time to their top line. The project is split into two milestones, data mining and
data analysis. 

Mining code is found in the `notebook/miner.ipynb` notebook and contains a demonstration of how shifts are transformed from raw data to
line combinations with ice time calculations. 

Analysis code is found in `notebook/analyzer.ipynb` and contains an aggregation of top line usage per
team along with a simple visualization.

A third notebook, `notebook/shift_miner.ipynb` contains demo code that was used to build the final miner notebook.

## Setup Guide (MacOS)
* Clone repo in terminal `git clone https...`
* Install pip `python3 -m pip install --user --upgrade pip`
* Verify installation `python3 -m pip --version`
* Install virtual environment (allows us to download python packages) `python3 -m pip install --user virtualenv`
* Create virtual environment on machine `python3 -m venv env`
* Start virtualenv `source env/bin/activate`
* Install all packages from requirements.txt `pip install -r requirements.txt`
* Start jupyter notebook `jupyter notebook`
* Navigate to desired notebook throught the `notebook` folder
