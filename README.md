# ground-water-data-sources
Groundwater prediction using deep learning models
Getting the code
You can download a copy of all the files in this repository by cloning the git repository:

git clone https://github.com/DARE-ML/groundwater_deeplearning.git
or download a zip archive

Objective
The objective of this code repository is to provide the source code for analysis done in Deep learning for analysis of ground-water level via stream-flow and precipitation, to improve the transparency and enable reproducability of the results and further discussions found in the paper.

Input data format
The data used in the analysis can be found in the data folder, and the models can be found under jupyter notebook: modelling_ver.ipynb

Borehole data
Borehole data from boreholes 17-22 is provided in 15 minute intervals ranging from 2013 to 2020. The data provided includes the groundwater depth in metres with respect to the Australian Height Datum (mAHD)

The files provided are in a CSV format, and can be identified via the BH prefix.

Borehole details
Specifics about the boreholes, including location, depth and screen radius (both in mAHD) can be found in Middle Creek bore details.xlsx.

Weather station and surface measurements
Finally, weather station data used for this analysis can be found in Middle Creek weather station.zip, which includes rainfall (in mm). The streamflow data can be found in Middle Creek surface.csv, using the mAHD data for Stilling Well

Libraries used
Library	Comments
numPy	Standard vector and matrix processing package
pandas	Data analysis and data manipulation tool
matplotlib	Used in visualisations of data and results
tensorflow	Primary source of neural network architecture
sklearn	Supplementary tools for metrics and evaluation
