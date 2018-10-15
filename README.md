# image-analysis-notebooks

The project contains jupyter notebook about bio-image-analysis. Beakerx will be used to allow mixing python and java.

## Installation
You need to have [anaconda](https://www.anaconda.com/download/#linux) and [FIJI](http://fiji.sc/) installed. Clone the repository. 

Open the env.yml file in a text editor and modify the last line. Replace 
`prefix: /home/baecker/anaconda3/envs/beaker`
by `/home/<your_username>/anaconda3/envs/beaker`

From the directory containing the file `env.yml` call `conda env create -f env.yml`. Once the environment is installed, activate it  with `source activate beaker`. Run jupyter notebook with the command `beakerx`.

Follow the instructions in the notebook to access ImageJ and python.


