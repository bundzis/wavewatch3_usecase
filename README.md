# Data Component Use Case for Wave Power Calculation
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/bundzis/wavewatch3_usecase/blob/main/LICENSE.txt)

This [Jupyter Notebook](wavepower_usecase.ipynb) demonstrates how to use the 
[CSDMS Data Component](https://csdms.colorado.edu/wiki/DataComponents) to download surface wave properties from 
the WAVEWATCH III model output for a given time period, interpolate it to a specific location, 
and calculate the wave power over time at that point.

This Jupyter Notebook is part of the work for a research paper 
["CSDMS Data Components: data-model integration tools for Earth surface processes modeling"](https://doi.org/10.5194/gmd-2023-127).

### Notebook Citation
Undzis, B., Moriarty, J. M. (2023) Data Component Use Case for Wave Power Calculation, 
HydroShare, https://doi.org/10.4211/hs.b044425647e146229a778d59b164d7cf


### Run the Notebook
You can choose the following methods to run this Jupyter Notebook: 

#### Method 1: HydroShare
Please go to the [HydroShare Resource](http://www.hydroshare.org/resource/b044425647e146229a778d59b164d7cf) 
and follow the instruction in the **"Abstract"** section to run this notebook.

#### Method 2: CSDMS
Please go to the [CSDMS EKT Lab](https://csdms.colorado.edu/wiki/Lab-0033) 
and follow the instruction in the **"Lab notes"** section to run this notebook.


#### Method 3: Local PC
Please first download all the files from this repository and have 
[conda](https://conda.io/projects/conda/en/latest/user-guide/install/index.html) installed on the local PC.
Then, use the following commands to create a virtual environment and launch the Jupyter Notebook. The code below works best on Mac OS or Linux and may cause some errors on Windows.
```
$ cd wavewatch3_usecase
$ conda env create --file=environment.yml
$ conda activate wavepower_usecase
$ jupyter notebook
```
