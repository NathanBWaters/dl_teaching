# dl_teaching
Repositories for my teaching engagements


## Installing What You'll Need

The first step to get running with these tutorials is to install virtualenv. Fortunately there is a [great tutorial](https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv) on hitchhiker's guide to python. Please follow the steps in the guide.

Once you have installed virtualenv let's make an enviornment with the following command:

`virtualenv -p python3 env`

You will want to be using python 3.6, so please make sure your enviornment is running it.

Again the tutorial is a great resource on showing you how to do this on both windows and mac:

[Activate your env](https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv)

The next step is that we will need to install all the requirements:

`pip install -r requirements.txt`

Finally the last step is to run an ipython notebook from within the env and then we are ready to go:

`ipython notebook`
