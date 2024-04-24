# Wikimedia Edits and Editors by Country

## Overview

This project provides a Jupyter Notebook that visualizes the edits and editors of Wikimedia projects for each country. The data is sourced directly from the Wikimedia Foundation and has been processed to maintain privacy through differential privacy techniques.

## Features

* **Dynamic Visualization** : Instantaneous plots showcasing edits and editors for Wikipedia, Wikimedia Commons, and Wikidata.
* **Country-specific Data** : Easily adjustable to view data for different countries.
* **User Level Segmentation** : Options to segment data based on user levels.
* **Data Frequency** : Choice between monthly or weekly data representation.

## Getting Started

### Prerequisites

* Python 3.x
* Jupyter Notebook
* Pandas
* Matplotlib
* Requests

### Installation

1. Clone the repository:
   <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><span class="" data-state="closed"></span></div></div></pre>

* <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/yourusername/wikimedia-edits-analysis.git
  </code></div></div></pre>
* Navigate to the project directory:
  <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><span class="" data-state="closed"></span></div></div></pre>
* <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">cd wikimedia-edits-analysis
  </code></div></div></pre>
* Install required packages:
  <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="flex items-center relative text-token-text-secondary bg-token-main-surface-secondary px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span class="" data-state="closed"></span></div></div></pre>

1. <pre><div class="dark bg-gray-950 rounded-md border-[0.5px] border-token-border-medium"><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs">pip install -r requirements.txt
   </code></div></div></pre>

## Usage

1. Open the `Wikimedia_Edits_Analysis.ipynb` notebook in Jupyter Notebook.
2. Adjust the country variable to your desired country.
3. Choose the data frequency (monthly or weekly).
4. Run the notebook to generate visualizations.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See `LICENSE` for more details.

## Acknowledgments

* Data sourced from the Wikimedia Foundation.
* Inspiration and initial structure from the provided example by Wikimedia.
