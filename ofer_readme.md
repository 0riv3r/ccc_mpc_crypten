# CrypTen
### Ofer's descryption

## Setup CrypTen

	$ conda create -n crypten python=3.7.0
	$ conda activate crypten
	$ python --version
	Python 3.7.0

	$ cd workspace
	$ git clone git@github.com:facebookresearch/CrypTen.git
	$ cd ~/workspace/CrypTen

	$ pip install crypten
	$ pip install -r requirements.examples.txt
	$ python examples/tfe_benchmarks/launcher.py --help

	$ pip install chardet
	$ conda install ipython jupyter
	$ conda install jupyterlab
	$ conda install -c anaconda ipykernel
	$ python -m ipykernel install --user --name=crypten

	$ cd tutorials/
	$ jupyter lab


