# Robotics Practice notebook
 Robotik und Mensch-Maschine-Interaktion 1 @ RWTH-Aachen
 2020 Winter Semester
### Author: Yu-Wen Chen 
email: yu.wen.chen@rwth-aachen.de

## This is the way ... to start
1. [Install Jupyter Notebook](https://jupyter.org/install)

2. Clone this repo. 
``` bash
cd ~/ && git clone https://github.com/airuchen/robotics_jupyter_notebooks.git && cd ~/robotics_jupyter_notebooks
```
3. Set up python3 environment and Install dependencies.
``` bash
python3 -m venv robotics-env
source robotics-env/bin/active
pip3 install ipywidgets
jupyter nbextension enable --py widgetsnbextension
pip3 install ipython
```
4. Run jupyter notebook
``` bash
cd ~/robotics_jupyter_notebooks
jupyter notebook
```
5. voilà