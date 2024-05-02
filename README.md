# Wikimedia Edits and Editors by Country

## Overview

This project provides a Jupyter Notebook that visualizes the edits and editors of Wikimedia projects for a country of a choice. The data is sourced directly from the Wikimedia Foundation and has been processed to maintain privacy through differential privacy techniques. You can find more information about the dataset [here](https://analytics.wikimedia.org/published/datasets/geoeditors_monthly/00_README.html).

The initial set-up was done by HTriedman (WMF), and you can find the example [here](https://public-paws.wmcloud.org/User:HTriedman%20(WMF)/private_geoeditors_data_access.ipynb).

## Features

* **Visualization** : Instantaneous plots showcasing edits and editors for Spanish Wikipedia, Wikimedia Commons, and Wikidata.
* **Country-specific Data** : Easily adjustable to view data for different countries.
* **Data Frequency** : Choice between monthly or weekly data representation.

## Getting Started

### Prerequisites

* Python 3.x
* Jupyter Notebook
* Pandas
* Matplotlib
* Requests
* Seaborn

### Installation

You can either download the monthly or weekly code and run it on your computer. Or you can use an online Notebook, for example PAWS. 

## Usage

1. Open the `geoeditors_monthly.ipynb`  or the `geoeditors_weekly.ipynb` notebook in Jupyter Notebook.
2. Adjust the country variable to your desired country.
3. Run the notebook to generate visualizations.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the GNU General Public License v3.0. See `LICENSE` for more details.

## Acknowledgments

* Data sourced from the Wikimedia Foundation.
* Inspiration and initial structure from the provided example by HTriedman (WMF).
