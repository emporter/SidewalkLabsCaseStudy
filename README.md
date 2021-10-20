# SidewalkLabsCaseStudy
  Take home case study for Sidewalk Labs data scientist interview
  author: Emily Porter (emilysporter@gmail.com)

#### Overview:
	  * An Anaconda Jupyter notebook running Python 3.9 reads the data files from web and generates visualizations to show:
		  * - global energy generation by source in 2018
		  * - global electricity consumption by end use between 2008-2018
	  * The notebook contains additional descriptions of the underlying data set in markdown boxes and also outlines potential future investigations to pursue
	  using the same data.

#### Libraries:
	* pandas as pd
	* urllib.request
	* bs4 (BeautifulSoup)
	* requests
	* numpy
	
#### Other dependencies:
	* Jupyter notebook to specify plotting settings ('plot_settings.ipynb')
	* 3 csv files located in folder 'helper files'
	* file 1: 'source_to_code' contains 2 columns, 1 of electricity sources and 1 of their associated United Nations assigned source code (2 letters)
	* file 2: 'source_weight_to_energy' contains 2 columns, 1 of electricity sources and 1 of their associated weight to energy conversion (from metric tons to gigajoules)
	* file 3: 'source_to_efficiency' contains 2 columns, 1 of electricity sources and 1 of their approximate power plant efficiency

#### Instructions:
	Open the Jupyter notebook in web browser (Anaconda must be installed) and run all cells. Webscraping the data is the slowest part of the notebook. After 
	running, scroll down through the notebook to see visualizations and additional notes in markdown boxes.

