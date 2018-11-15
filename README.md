# iahl-adjusted-standings
A python notebook that:

* connects to the Yahoo API and fetches the current standings for IAHL
* adjusts the standings based on games played
* calculates rotisserie scores for the adjusted numbers
* calculates a normalized score on the adjusted standings

## Prerequisites

* Python 3 environment with virtualenvironments
* App keys from yahoo

## How-to

* clone the repository to a local location `git clone https://github.com/iahl-discussions/iahl-adjusted-standings.git`
* create a virtualenvironment in the downloaded directory `python -m venv iahl-adjusted-standings`
* activate the virtual environment `source iahl-adjusted-standings/bin/activate`
* go into the directory `cd iahl-adjusted-standings/`
* install the dependencies `pip install -r requirements.txt`
* create a kernel to run the notebook with `ipython kernel install --user --name=iahl-adjusted-standings`
* create the folder `resources` and create a new file `credentials.json` that looks like this:

`{
    "consumer_key": "consumer key for your app (found at yahoo developer)",
    "consumer_secret": "consumer secret for your app (found at yahoo developer)",
}`

Launch jupyter notebooks/labs `jupyter lab` and open `api-test.ipynb`
