# data-conversion
Example for loading Parquet files generated from sparse arff files. Aid to other OpenML devs.

## Installation
It is recommended to create a virtual environment first: `python -m venv venv`

Then activate it and install the requirements there: `source venv/bin/activate` and `python -m pip install -r requirements.txt`.

Then you can start Jupyter lab and start the notebook: `jupyter-lab`.

Note that the data of the last file, `masked_pyarrow.pq`, is slightly different: 0 values are masked as NaN, which also obscures values which were originally NaN. We would change this for the final conversion.
