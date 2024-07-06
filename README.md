# Sacramento Data App Using Bokeh

One aspect of data science is communicating results to stakeholders. One way to do this is to create a data app that allows stakeholders to interact with the data themselves. This is also a great way to explore the data yourself. This project contains a simple notebook that creates a data app using [Bokeh](https://docs.bokeh.org/en/latest/index.html#) to visualize data from the Sacramento real estate transactions dataset. 

## Installation

Run the following command to install the required python packages.

```bash
pip install -r requirements.txt
```

## Usage

Start a jupyter server to run the notebook. The default port is 8888. See more information on how to start a jupyter server [here](https://docs.jupyter.org/en/latest/running.html).

```bash
jupyter notebook
```

Once the notebook is open, run the cells to see the visualizations. Note: The interactive visualization in part III does not work in an IDE like PyCharm or Visual Studio Code. Running the notebook in a browser from a jupyter server is required.

# Dataset

The dataset used in this project consists of Sacramento real estate transactions in 2008. The dataset has been cleaned and has been saved as a feather file in data/cleaned_sacramento_real_estate_transactions.

| Column Name | Description | Data Type |
| ----------- | ----------- | --------- |
| street | Street address | string |
| city | City | category |
| zip | Zip code | category |
| state | State | category |
| beds | Number of bedrooms | category |
| baths | Number of bathrooms | category |
| sq__ft | Square footage | int64 |
| type | Type of property | category |
| sale_date | Date of sale | string |
| price | Price of property | int64 |
| latitude | Latitude | float64 |
| longitude | Longitude | float64 |
| empty_lot | If the lot is empty | bool |
| street_type | Type of street (st. ct, way, etc.)| category |