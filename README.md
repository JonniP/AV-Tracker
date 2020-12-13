# AV-Tracker
Neural network for aerial vehicle tracking.

## Running steps
- Clone the repository.
- Navigate to the root folder.
- Create a virtual environment: python -m venv AVvenv
- Activate the environment (Windows): .\AVvenv\Scripts\activate
- Install dependencies using pip install -r requirements.txt
- From the root folder, run jupyter using command: jupyter notebook and open file AVtracker.ipynb.
- Run all cells except the image testing cell, as there are currently no test images.
- Video testing cell uses the model and outputs the result file to Saved_videos.


## Problem documentation
- Python version must be 64bit 3.5-3.8 due to Tensorflow support.
- If you get error *tensorflow has no attribute compat* while running the import cell, do the following steps:
	-> pip install tensorflow-estimator==2.1.*
	-> pip install -r requirements.txt
	-> For some reason installing the wrong version and installing the estimator from requirements file works.

