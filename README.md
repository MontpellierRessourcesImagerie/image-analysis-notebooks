# image-analysis-notebooks

The project contains jupyter notebook about bio-image-analysis. Beakerx will be used to allow mixing python and java.
 
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/MontpellierRessourcesImagerie/image-analysis-notebooks/v1.0.2)

Note: The parts that launch the ImageJ gui interface from a notebook will only work when you run it locally, not on the server via mybinder.

## Installation

You need to have [anaconda](https://www.anaconda.com/download/#linux) and [FIJI](http://fiji.sc/) installed. Clone the repository. 

From the directory containing the file `env.yml` call `conda env create -f env.yml`. Once the environment is installed, activate it  with `source activate beaker`. Run jupyter notebook with the command `beakerx`.

Follow the instructions in the notebook to access ImageJ and python.


