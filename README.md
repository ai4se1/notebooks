# LLM Debugging Assistant - Evaluation

This repo contains notebooks to evaluate the defect detection capabilities of the LLM Debugging Assistant.

During the project, we explored two approaches for which we created two separate notebooks.

## Setup

To run the notebooks you need to have `python3.12` installed together with the dependencies listed in `requirements.txt`. You can install them by running `pip install -r requirements.txt`.

Afterward, you can use the notebooks in two ways:

### Run benchmarks by calling the API

If you want to run a new benchmark you need to ensure that the LLM debugging assistant backend is accesible at `http://delos.eaalab.hpi.uni-potsdam.de:8010/highlight-code/`. Checkout the corresponding repository for setup instructions.

Also, note that processing all entries takes a significant amount of time, so you might want to run the notebook on a server.

### Evaluate the results

If you only want to evaluate the results you can skip the cells that call the API. We provide the results and intermediate results for our second approach in the `results` folder. You can run the evaluation scripts by importing the relevant csv files as dataframes.
