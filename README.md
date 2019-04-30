# A Machine Learning Intro by ACM AUTH Student Chapter

_Getting started with Machine Learning_

## Setting up your Dev environment ##
`- Python - Libraries - Editor`

`- Working online & offline`

### Python Installation ###

Version: **Python 3.6.+** (not 2.7 or 3.7)

#### Manual installation _(Not Recommended)_ #### 

**Windows** - [Download](https://www.python.org/downloads/windows/)
- Preferably use **Anaconda (see below)**
- Or move to Unix Based System ![](https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/240/apple/155/smiling-face-with-open-mouth-and-cold-sweat_1f605.png =15x)

**Linux Based** -  Already Installed
- Check version: `python --version `  or  `python3 --version`
- Update/ Install: `sudo apt-get install python3`
- Can also use **Anaconda (see below)**

**macOS** - Follow this [guide](https://docs.python-guide.org/starting/install3/osx/) or use **Anaconda (see below)**


#### Anaconda Installation **_(Recommended)_**

Anaconda is a **downloadable, free, open source, high-performance and optimized Python distribution**.

Anaconda includes: 
- [conda](https://conda.io/projects/conda/en/latest/index.html) & conda build
- Python (choose version, change versions easily)
- 100+ automatically installed, open source scientific packages and their dependencies that have been tested to work well together, including SciPy, NumPy and many others. 

**-- Includes everything that you need and is the best for new users--**

Available for [Windows](https://www.anaconda.com/distribution/#windows), [macOS](https://www.anaconda.com/distribution/#macos) and [Linux](https://www.anaconda.com/distribution/#linux), all versions of Anaconda are supported by the community.



---



**Conda environments**

With conda, you can create, export, list, remove, and update environments that have different versions of Python and/or packages installed in them. Switching or moving between environments is called activating the environment. You can also share an environment file.

**Available Python is 3.7. You can downgrade it to 3.6.6 with `conda install python=3.6`**


**Using the command line:**

- Verify conda is installed, check version number: `conda info`
- Install package: `pip install package_name` or `conda install package_name`
- Create new empty environment named ENVNAME: `conda create --name ENVNAME` or clone an existing environment `conda create --name ENVNAME --clone EXISTING_ENVIRONMENT`
- Activate a named conda environment `conda activate ENVNAME`
- Deactivate the current environment `conda deactivate`
- List all packages and versions in the active environment `conda list`
- More commands on environments [here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)


#### Important Libraries for Machine Learning ####
_WILL BE UPDATED ACCORDINGLY_


**[NumPy](http://www.numpy.org/)** -> N-dimensional array for numerical computation.

**[Pandas](http://pandas.pydata.org/)** -> Powerful Python data structures and data analysis toolkit.

**[scikit-learn](https://scikit-learn.org/stable/)** -> Python modules for machine learning and data mining

**[Matplotlib](https://matplotlib.org/)** **[Seaborn](https://seaborn.pydata.org/)** **[Bokeh](https://bokeh.pydata.org/en/latest/)** -> Plotting libraries for Python

**[NLTK](https://www.nltk.org/)** **[Gensim](https://radimrehurek.com/gensim/)**  -> The leading platforms for building Python programs to work with human language data.

**[TensorFlow](https://www.tensorflow.org/)** **[Keras](https://keras.io/)** **[PyTorch](https://pytorch.org/)** -> Deep learning frameworks


## IDEs and Notebooks ##

### All in one IDEs ###


#### [PyCharm](https://www.jetbrains.com/pycharm/) ####

*  Go for the ultimate version as a student  
*  Has everything you'll ever need (editor, auto-compeltion, debugger, database connect, a ton of plugins)
* Perfect if you already use JetBrains products
* Works with Anaconda (can create environments), remote interpreters and native python.
* Version Control (Git etc.) & Deployment

#### [Spyder](https://www.spyder-ide.org/) #### 
* Also cool, and open source
* Better for begginers and those coming from R Studio and MatLab...
* Variable Explorer

#### Notebooks ####

##### [Jupyter Notebook](https://jupyter.org/) #####

The notebook extends the console-based approach to **interactive computing** in a qualitatively new direction, providing a web-based application suitable for capturing the whole computation process: developing, documenting, and executing code, as well as communicating the results. 

* Forget all the above, just a notebook - just for scripting
* Easy to use, comes with Anaconda
* A web application,  combine explanatory text, mathematics, computations and their rich media output.
* Work from your browser, lightweight, further installs
* Execute code in pieces and in any way you want.

[Command Cheatsheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Jupyter_Notebook_Cheat_Sheet.pdf) - Applies to Colab also

##### [Google Colaboratory](https://colab.research.google.com/) or just Colab! #####

*A jupyter notebook online* 

* No installation, both CPU and GPU/TPU usage
* Aims to collaboration and sharing 
* Added support - LaTex Mathematics
* Can also run on your local Python Installation
* Interaction with GitHub and Google Drive


## You first machine learning code ##

### Presentations ###

<img src="https://scontent.fath4-2.fna.fbcdn.net/v/t1.0-9/41466094_2133085533624950_2793870230273654784_n.png?_nc_cat=107&_nc_ht=scontent.fath4-2.fna&oh=fa9b3a22401b3fefed1e438bd9d13707&oe=5D2BE64B" alt="sfhmmy_logo" width="200"/>


[ΣΦΗΜΜΥ11 2019](https://github.com/acmauth/mlintro/blob/master/Machine%20Learning%20Intro.pdf)


### Notebooks ###

[ΣΦΗΜΜΥ11 2019](https://github.com/acmauth/mlintro/blob/master/Machine_Learning_Intro.ipynb)

### Datasets ###

[California Housing Dataset (with ocean proximity)](https://github.com/acmauth/mlintro/blob/master/housing.csv)