# SafeCity-Sprint-2018
- [What is a Sprint?](https://github.com/DataKind-BLR/Sprint/wiki)
- [About SafeCity](https://github.com/DataKind-BLR/SafeCity-Sprint-2018/blob/master/README.md#about-safecity)
- [About the Dataset](https://github.com/DataKind-BLR/SafeCity-Sprint-2018#data-description)
- [What would you like to solve for SafeCity?](https://github.com/DataKind-BLR/SafeCity-Sprint-2018/issues)
- [Getting started with Github](https://github.com/DataKind-BLR/SafeCity-Sprint-2018/blob/master/README.md#about-git
) 


## About SafeCity

[Web](http://safecity.in/) | [Android App](https://play.google.com/store/apps/details?id=com.safecity)

[Safecity](http://safecity.in/) aims to make cities safer by encouraging equal access to public spaces for everyone especially women, through the use of crowdsourced data and technology. Since the launch on 26 Dec 2012 SafeCity has collected over 10,000 stories from over 50 cities in India, Kenya, Cameroon and Nepal. Main objective of the organisation is to:

• Create awareness on street harassment and abuse and get women and other disadvantaged communities to break their silence and report their personal experiences. 

• Collate this information to showcase location based trends.

• Make this information available and useful for individuals, local communities and local administration to solve the problem at the local level.

![SafeCity](https://user-images.githubusercontent.com/12103383/41036984-844c70e8-69af-11e8-81e5-c23847b1c8bd.png)

Target group are women/girls who are victims of sexual harassment. SafeCity is creating a new data set which currently does not exist and moves the focus away from the “victim” to the location so that people can view the issue with a different lens.

Also people can sign up for alerts either based on location or category of harassment. This allows people to understand the “safety” landscape of an area and make the most informed decision for themselves. 

## Data Description

Rows in the dataset represent reports filed by a user.

| Column(s)        | Description           | Data Type  |
| ------------- |:-------------:| -----:|
| INCIDENT ID      |  A unique ID for each report | String |
| INCIDENT TITLE       | A title provided by the victim      |   String |
| DATE | Date in mm/dd/yy     |    String |
| D-G      |  Values Derived from Date| String |
| TIME       | Time in hh:mm      |   String |
| I-K | Values Derived from Time     |    String |
| DESCRIPTION | Description of the report | String |

While filing a report, you need to select a 'Category'. M-Y are the categories. 1 indicates, Yes. 0 indicates No.

| Column(s)        | Description           | Data Type  |
| ------------- |:-------------:| -----:|
| M-Y | Report Category     |    Boolean |
| Z-AD      |  Grouping of Report Category | Boolean |
| Location       | Address    |   String |
| Country Code | Country Code  |    String |
| City Code      |  City Code | String |
| Area Code      |  Area Code   |   String |
| Locality Code | Locality Code    |    String |
| Latitude   |  Latitude of the Incident | String |
| LONGITUDE     |  Longitude of the Incident   |   String |

### Grouping of categories
_Verbal_ _Abuse_ - Catcalls, Commenting, Sexual Invites


_Non-Verbal_ _Abuse_ - Ogling/Facial Expression/Staring, Indecent Exposure


_Physical_ _Abuse_ - Touching/Groping, Stalking


_Serious_ _Physical_ _Abuse_ - Rape/ Sexual Assualt


_Other_ _Abuse_ - Poor / No Street Lighting	Chain Snatching	North East India Report	Others


## About Git

#### Getting started with Github
- https://try.github.io

#### Submitting a PR
- https://github.com/PointCloudLibrary/pcl/wiki/A-step-by-step-guide-on-preparing-and-submitting-a-pull-request
- https://yangsu.github.io/pull-request-tutorial/

#### Getting started with R
- https://support.rstudio.com/hc/en-us/articles/201141096-Getting-Started-with-R

#### Getting started with RMarkdown
- https://guides.github.com/features/mastering-markdown/

#### Getting started with Python
- http://learnpython.org/
- https://automatetheboringstuff.com/

#### Getting started with Jupyter 
- Notebooks - https://jupyter-notebook.readthedocs.io/en/stable/
- Lab - http://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html

#### Cloud Based Jupyter Environment
- Colaboratory - https://colab.research.google.com

#### Getting Started with Pandas
- http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/
- http://nbviewer.jupyter.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_1-Introduction-to-Pandas.ipynb
- http://nbviewer.jupyter.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section2_2-Data-Wrangling-with-Pandas.ipynb
- http://nbviewer.jupyter.org/github/fonnesbeck/Bios8366/blob/master/notebooks/Section0_2-Plotting-and-Visualization.ipynb

#### Hands-on NLTK Tutorial
- https://github.com/hb20007/hands-on-nltk-tutorial
- https://likegeeks.com/nlp-tutorial-using-python-nltk/

#### Data Science with Python
- https://github.com/donnemartin/data-science-ipython-notebooks
- https://github.com/jakevdp/PythonDataScienceHandbook/tree/master/notebooks

#### Machine Learning in Python
- https://in.udacity.com/course/intro-to-machine-learning--ud120
- https://github.com/ageron/handson-ml

#### Deep Learning Resources
- https://github.com/ChristosChristofidis/awesome-deep-learning

#### Documentation of useful libraries in Python
- Numpy - http://www.numpy.org/
- Pandas - https://readthedocs.org/projects/pandas/
- Scikit Learn - http://sklearn-features.readthedocs.io/en/latest/
- NLTK - https://nltk.readthedocs.io/en/latest/
- Gensim - https://radimrehurek.com/gensim/tutorial.html
