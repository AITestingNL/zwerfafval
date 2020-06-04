How to set up the environment to run the code?

- [Python 3](https://www.python.org/)
- Optional:
  -  install [VirtualEnv](https://virtualenv.pypa.io/en/stable/)
     - `pip3 install virtualenv`
  - create a virtual environment
    - create a project folder
    - `cd project_folder`
    - `virtualenv venv`
  - activate the new created environment
    - `source venv/bin/activate`
- Clone the zwerfafval project into the project folder
  - `git clone https://github.com/AITestingNL/zwerfafval.git`
- Go to the zwerfafval folder
  - `cd zwerfafval`
- Install libraries from command line
  - `pip install -r requirements.txt`
- Start Jupyter
  - `jupyter notebook --notebook-dir=.`