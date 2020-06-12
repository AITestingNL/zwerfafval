How to set up the environment to run the code?

- Install [Python 3](https://www.python.org/. 64 bit version is needed since Tensorflow doesn't work with 32 bit version of Python.
- Optional:
  -  install [VirtualEnv](https://virtualenv.pypa.io/en/stable/)
     - `pip install virtualenv`
  - create a virtual environment
    - create a project folder
    - `cd project_folder`
    - `virtualenv venv`
  - activate the new created environment
    - `source venv/bin/activate` in Linux/Mac
    - `venv\Scripts\activate` in Windows
- Clone the zwerfafval project into the project folder
  - `git clone https://github.com/AITestingNL/zwerfafval.git`
- Go to the zwerfafval folder
  - `cd zwerfafval`
- Install libraries from command line
  - `pip install -r requirements.txt`
- Start Jupyter
  - `jupyter notebook --notebook-dir=.`


In the browser with Jupyter Notebook you can open `zwerfafval.ipynb` to modify and run the codes step by step