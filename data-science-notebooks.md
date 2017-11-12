# Data Science notebooks

The collection is just my favorite list of useful notebooks and examples on data science topics.
Some of them are collected from other sources (including text description). References for the orignal sources here: [References](#References) 


# Table of Contents

1. [Data Science, Data Analysis and Statistics](#data-science,-data-analysis-and-statistics)
    * [Useful tools and techniques for Data Science)](#useful-tools-and-techniqies-for-data-science)
    * [Statistics)](#statistics)
    * [Pandas)](#pandas)
        * [Pandas for data analysis](#pandas-for-data-analysis)

1. [Machine Learning](#machine-learnign)
    * [General ML materials](#general-ml-materials)
    * [Neural networks](#neural-networks)

1. [Natural Language Processing (NLP)](#natural-language-processing)
    * [Natural Language Processing](#natural-language-processing)
    * [Linguistics and Text Mining](#linguistics-and-text-mining)

1. [Visualize it](#visualize-it)
    * [Data visualization and plotting](#data-visualization-and-plotting)

1. [Programming and Computer Science](#programming-and-computer-science)

1. [Scientific computing and data analysis with the SciPy Stack](#scientific-computing-and-data-analysis-with-the-scipy-stack)
    * [General topics in scientific computing](#general-topics-in-scientific-computing)
    * [Social data](#social-data)
    * [Psychology and Neuroscience](#psychology-and-neuroscience)
    * [Physics, Chemistry and Biology](#physics-chemistry-and-biology)
    * [Economics and Finance](#economics-and-finance)
    * [Earth science and geo-spatial data](#earth-science-and-geo-spatial-data)
    * [Mathematics](#mathematics)
    * [Signal, Sound and Image Processing](#signal-and-sound-processing)
    
1. [Notebooks on specific topics](#entire-books-or-other-large-collections-of-notebooks-on-a-topic)
    * [Introductory Tutorials](#introductory-tutorials)* 
    * [Mathematics, Physics, Chemistry, Biology](#mathematics-physics-chemistry-biology)
    * [Earth Science and Geo-Spatial data](#earth-science-and-geo-spatial-data)
    * [Signal Processing](#signal-processing)
    * [Engineering Education](#engineering-education)



1. [Other publications using the Notebook](#other-publications-and-conference-abstracts-that-explicitly-use-the-notebook)

1. [Data-driven journalism](#data-driven-journalism)


## Data Science, Machine Learning and Statistics

### Useful tools and techniques for Data Science

* The code of the [IPython mini-book](https://github.com/rossant/ipython-minibook) by C. Rossant, introducing IPython, NumPy, SciPy, Pandas and matplotlib for interactive computing and data visualization.

* [Python Data Science Handbook Supplemental Materials](https://github.com/jakevdp/PythonDataScienceHandbook), a collection of notebooks by [Jake VanderPlas](http://vanderplas.com) to accompany the book.

* A collection of [four courses in foundations of data science, algorithms and databases](http://nbviewer.ipython.org/github/ledeprogram/courses/tree/master) from multiple faculty at [Columbia University's Lede Program](http://www.journalism.columbia.edu/page/1058-the-lede-program-an-introduction-to-data-practices/906). 

* [Data Science Notebooks](https://github.com/donnemartin/data-science-ipython-notebooks/blob/master/README.md), a frequently updated collection of notebooks on statistical inference, data analysis, visualization and machine learning, by [Donne Martin](https://github.com/donnemartin).

* [Learn Data Science](http://learnds.com), an entire self-directed course by [Nitin Borwankar](https://github.com/nborwankar).

* [IPython Cookbook](http://ipython-books.github.io/cookbook/) by [Cyrille Rossant](http://cyrille.rossant.net/), a comprehensive guide to Python for Data Science. The code of the 100 recipes is available on [the GitHub repository](https://github.com/ipython-books/cookbook-code).

* [Data Science and Big Data with Python](https://github.com/phelps-sg/python-bigdata/blob/master/README.md) by [Steve Phelps](http://sphelps.net).

* [Python for Data Analysis](https://github.com/ResearchComputing/Meetup-Fall-2013), an introductory collection from the [CU Boulder Research Computing Group](http://researchcomputing.github.io/).

* [ETL with Python](https://github.com/dimgold/ETL_with_Python/blob/master/README.md), a tutorial for ETL (Extract, Transfer and Load) using python [petl package](https://petl.readthedocs.io/en/latest/), loading to MySQL and working with csv files by [Dima Goldenberg](https://github.com/dimgold).

* [Python for Data Science](http://nbviewer.ipython.org/github/gumption/Python_for_Data_Science/blob/master/Python_for_Data_Science_all.ipynb), a self-contained mini-course with exercises, by [
Joe McCarthy](http://interrelativity.com/joe).

* [First few lectures of the UW/Coursera course on Data Analysis](http://nbviewer.ipython.org/github/fonnesbeck/ComputationalMethodsCourse/blob/master/Lecture%201.ipynb). ([Repo](https://github.com/fonnesbeck/ComputationalMethodsCourse)) by Chris Fonnesbeck.



### Statistics 

* The [Statsmodels Project](http://statsmodels.sourceforge.net) has two excellent collections of examples: [in their official documentation](http://statsmodels.sourceforge.net/devel/examples/index.html) and [extra ones in their wiki](https://github.com/statsmodels/statsmodels/wiki/Examples#user-contributed-examples). Too many there to directly duplicate here, but they provide great learning materials on statistical modeling with Python.

* ["ISP": Introduction to Statistics with Python](https://github.com/thomas-haslwanter/statsintro_python), a collection of notebooks accompanying the [book of the same name](http://www.springer.com/us/book/9783319283159), by [Thomas Haslwanter](http://work.thaslwanter.at).

* [Understanding model reliability](http://nbviewer.ipython.org/github/mwaskom/Psych216/blob/master/week6_tutorial.ipynb), part of a complete [course on statistics and data analysis for psychologists](https://github.com/mwaskom/Psych216) by [Michael Waskom](https://github.com/mwaskom).

* [Graphical Representations of Linear Models](http://nbviewer.ipython.org/github/mwaskom/seaborn/blob/master/examples/linear_models.ipynb), an illustration of the [Seaborn statistical visualization library](https://github.com/mwaskom/seaborn), that also includes [Visualizing distributions of data](http://nbviewer.ipython.org/github/mwaskom/seaborn/blob/master/examples/plotting_distributions.ipynb) and [Representing variability in timeseries plots](http://nbviewer.ipython.org/github/mwaskom/seaborn/blob/master/examples/timeseries_plots.ipynb). By [Michael Waskom](https://github.com/mwaskom).

* [Desperately Seeking Silver](http://nbviewer.ipython.org/github/cs109/content/blob/master/HW2.ipynb), one of the homework sets for Harvard's [CS 109 Data Science course](http://cs109.org).

* The classic ['An Introduction to Statistical Learning with Applications in R'](http://www-bcf.usc.edu/~gareth/ISL) by James, Witten, Hastie, Tibshirani (2013), has not one but *two* collections of notebooks to accompany the book with Python (instead of the book's default R examples). One by [Jordi Warmenhoven](https://github.com/JWarmenhoven/ISLR-python) and one by [Matt Caudill](https://github.com/mscaudill/IntroStatLearn).

* [Python Notebooks for StatLearning Exercises](https://github.com/sujitpal/statlearning-notebooks), Python implementations of the R labs for the [StatLearning: Statistical Learning](https://class.stanford.edu/courses/HumanitiesScience/StatLearning/Winter2014/about) online course from Stanford University taught by Profs Trevor Hastie and Rob Tibshirani.

* [An introduction to Bayesian inference](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter1_Introduction/Chapter1.ipynb), this is just chapter 1 in an ongoing book titled [Probabilistic Programming and Bayesian Methods for Hackers Using Python and PyMC](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers), by [Cameron Davidson-Pilon](http://camdp.com/).

* [Doing Bayesian Data Analysis](https://github.com/JWarmenhoven/DBDA-python): Python/PyMC3 code for a selection of models and figures from the book _'Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan'_, Second Edition, by John Kruschke (2015).  

* [Applied Predictive Modeling with Python](http://nbviewer.ipython.org/github/leig/Applied-Predictive-Modeling-with-Python/tree/master/notebooks/), Python implementations of the examples (originally written in R) from a famous introductory book, [Applied Predictive Modeling](http://appliedpredictivemodeling.com), by Max Kuhn and Kjell Johnson.

* [Kalman and Bayesian Filters in Python](http://nbviewer.ipython.org/github/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/table_of_contents.ipynb), by [Roger Labbe](https://github.com/rlabbe).

* [An introductory notebook on uncertainty quantification and sensitivity analysis](http://nbviewer.jupyter.org/github/lrhgit/uqsa_tutorials/blob/master/index.ipynb) developed for the [Workshop On Uncertainty Quantification And Sensitivity Analysis For
Cardiovascular Modeling](http://sathercenter.berkeley.edu/peder-sather-grant/2016-grantees/)
by [Leif Rune Hellevik](https://github.com/lrhgit), Vinzenz Eck and Jacob T. Sturdy.

* [AM207: Monte Carlo Methods, Stochastic Optimization](http://am207.github.io/2016/): a complete course by Verena Kaynig-Fittkau and Pavlos Protopapas from Harvard, with all lecture materials and homework sets as notebooks.


### Pandas 

* [An introduction to Pandas](http://nbviewer.ipython.org/urls/bitbucket.org/hrojas/learn-pandas/raw/master/lessons/01%20-%20Lesson.ipynb), part of an [11-lesson tutorial on Pandas](https://bitbucket.org/hrojas/learn-pandas), by [Hernán Rojas](https://bitbucket.org/hrojas).

* [Pandas .head() to .tail()](https://github.com/TomAugspurger/PyDataSeattle), an in-depth tutorial on Pandas by [Tom Augspurger](https://github.com/TomAugspurger).

* [Effective Pandas](https://github.com/TomAugspurger/effective-pandas), a collection of notebooks behind my series on writing idiomatic pandas by [Tom Augspurger](https://github.com/TomAugspurger). Also check archived [Modern Pandas](https://tomaugspurger.github.io/modern-1-intro)

* [A 10-minute whirlwind tour of pandas](http://nbviewer.ipython.org/gist/wesm/4757075/PandasTour.ipynb), this is the notebook accompanying a [video presentation](http://vimeo.com/59324550) by Wes McKinney, author of Pandas and the [Python for Data Analysis](http://www.amazon.com/Python-Data-Analysis-Wes-McKinney/dp/1449319793) book.

* [Time-series analysis with Pandas](http://nbviewer.ipython.org/github/changhiskhan/talks/blob/master/pydata2012/pandas_timeseries.ipynb).

* [Financial data analysis with Pandas](http://nbviewer.ipython.org/gist/3962843).

* [Clustering of smartphone sensor data for human activity detection using pandas and scipy](http://nbviewer.ipython.org/github/herrfz/dataanalysis/blob/master/week4/clustering_example.ipynb), part of Coursera data analysis course, done in Python ([repo](https://github.com/herrfz/dataanalysis)).

* [Log analysis with Pandas](http://nbviewer.ipython.org/url/taaviburns.ca/presentations/log_analysis_with_pandas/nb/5-Scatterplots.ipynb), part of a [group presented at PyConCa 2012](http://taaviburns.ca/presentations/log_analysis_with_pandas/) by Taavi Burns.

* [Analyzing and visualizing sun spot data with Pandas](http://nbviewer.ipython.org/gist/4569783), by [Josh Hemann](https://github.com/jhemann). An enlightening discussion of how naive plotting choices subtly influence our interpretation of data.

* [Advanced analysis of Apache logs](http://nbviewer.ipython.org/github/koldunovn/nk_public_notebooks/blob/master/Apache_log.ipynb), by [Nikolay Koldunov](https://github.com/koldunovn).

* [Statistical Data Analysis in Python](https://github.com/fonnesbeck/statistical-analysis-python-tutorial), by [Christopher Fonnesbeck](https://github.com/fonnesbeck/), SciPy 2013. Companion videos [1](https://www.youtube.com/watch?v=DXPwSiRTxYY), [2](https://www.youtube.com/watch?v=TGEBpzJUxdI), [3](https://www.youtube.com/watch?v=YZDtBEEZuAk), [4](https://www.youtube.com/watch?v=5_rcdhBXD-0)



### Kaggle examples

* [The Kaggle bulldozers competition example](http://danielfrg.github.io/blog/2013/03/07/kaggle-bulldozers-basic-cleaning), one of a set on tutorials on exploratory data analysis with the [copper toolkit](https://github.com/danielfrg/copper#copper) by [Daniel Rodríguez](http://danielfrg.github.io)/

* [Kaggle Competition: Titanic Machine Learning from Disaster](http://nbviewer.ipython.org/github/agconti/kaggle-titanic/blob/master/Titanic.ipynb). By [Andrew Conti](https://github.com/agconti).



## Machine Learning

### General ML materials 
* [Notes on Machine Learning & Artificial Intelligence](https://chrisalbon.com/), by [Chris Albon](https://chrisalbon.com/pages/about.html)

* [An introduction to machine learning with Python and scikit-learn](http://nbviewer.ipython.org/github/temporaer/tutorial_ml_gkbionics/blob/master/2%20-%20KMeans.ipynb) ([repo and overview](https://github.com/amueller/tutorial_ml_gkbionics)) by [Hannes Schulz](https://github.com/temporaer) and [Andreas Mueller](https://github.com/amueller).

* [Clustering and Regression](http://nbviewer.ipython.org/github/amplab/datascience-sp14/blob/master/hw2/HW2.ipynb), part of the UC Berkeley 2014 [Introduction to Data Science](http://amplab.github.io/datascience-sp14/) course taught by [Michael Franklin](http://www.cs.berkeley.edu/~franklin/).

* [Machine learning in Python](http://nbviewer.jupyter.org/github/jdwittenauer/ipython-notebooks/blob/master/notebooks/ml/ML-Exercise1.ipynb), a series based on Andrew Ng's Coursera class on machine learning.  Part of a [larger collection of data science notebooks](https://github.com/jdwittenauer/ipython-notebooks) by [John Wittenauer](https://github.com/jdwittenauer).

* [Notebooks for the exercises in Andrew Ng's online ML course, Spark and TensorFlow](https://github.com/jdwittenauer/ipython-notebooks), as well as extra material on other tools from the scipy stack, by [John Wittenauer](https://github.com/jdwittenauer).

* [An example machine learning notebook](http://nbviewer.jupyter.org/github/rhiever/Data-Analysis-and-Machine-Learning-Projects/blob/master/example-data-science-notebook/Example%20Machine%20Learning%20Notebook.ipynb), by [Randal. S. Olson](http://www.randalolson.com/), part of a [collection in Data Analysis and Machine Learning](http://nbviewer.jupyter.org/github/rhiever/Data-Analysis-and-Machine-Learning-Projects).

* [Apache SINGA tutorial](http://nbviewer.jupyter.org/github/apache/incubator-singa/blob/master/doc/en/docs/notebook/index.ipynb). A Python tutorial for deep learning with SINGA.

* [Adaboost for digit classification](https://nbviewer.jupyter.org/github/riddhishb/ipython-notebooks/blob/master/Adaboost/Adaboost_Final%20note.ipynb
), by [Shashwat Shukla](https://github.com/ShashShukla). A complete implementation of Adaboost in Python, with code for digit recognition. 
 
* [A tutorial introduction to machine learning with sklearn](http://amueller.github.com/sklearn_tutorial), an IPython-based slide deck by [Andreas Mueller](https://github.com/amueller).

* [Introduction to Machine Learning in Python with scikit-learn](http://ipython-books.github.io/featured-04/) by [Cyrille Rossant](http://cyrille.rossant.net/), a free recipe from the [IPython Cookbook](http://ipython-books.github.io/cookbook/), a comprehensive guide to Python for Data Science.

* [An introduction to Predictive Modeling in Python](http://nbviewer.ipython.org/github/ogrisel/parallel_ml_tutorial/blob/master/solutions/01%20-%20An%20Introduction%20to%20Predictive%20Modeling%20in%20Python.ipynb), by  [Olivier Grisel](https://github.com/ogrisel).

* [Face Recognition on a subset of the Labeled Faces in the Wild dataset](http://nbviewer.ipython.org/github/ogrisel/notebooks/blob/master/Labeled%20Faces%20in%20the%20Wild%20recognition.ipynb), by [Olivier Grisel](http://github.com/ogrisel).

* [An Introduction to Bayesian Methods for Multilevel Modeling](http://nbviewer.ipython.org/github/fonnesbeck/multilevel_modeling/blob/master/multilevel_modeling.ipynb), by [Chris Fonnesbeck](http://github.com/fonnesbeck).

* [Introduction to Bayesian Networks](http://nbviewer.ipython.org/github/kuitang/hackny-bayesnet/blob/master/hackNY%20Bayesian%20Network%20Demo.ipynb) by [Kui Tang](https://github.com/kuitang)

* [Bayesian data analysis with PyMC3](http://nbviewer.ipython.org/github/twiecki/pymc3_talk/blob/master/bayesian_pymc3.ipynb) by [Thomas Wiecki](https://github.com/twiecki).

* [A collection of examples for solving pattern classification problems](https://github.com/rasbt/pattern_classification), by [Sebastian Raschka](https://github.com/rasbt).

* [Introduction to Linear Regression using Python](http://nbviewer.ipython.org/github/justmarkham/DAT4/blob/master/notebooks/08_linear_regression.ipynb) by [Kevin Markham](https://github.com/justmarkham)

* [Machine learning in Python](http://nbviewer.jupyter.org/github/jdwittenauer/ipython-notebooks/blob/master/notebooks/ml/ML-Exercise1.ipynb), a series based on Andrew Ng's Coursera class on machine learning.  Part of a [larger collection of data science notebooks](https://github.com/jdwittenauer/ipython-notebooks) by [John Wittenauer](https://github.com/jdwittenauer).

* [Probability, Paradox, and the Reasonable Person Principle](http://nbviewer.ipython.org/url/norvig.com/ipython/Probability.ipynb), by Peter Norvig.

* [How Likely Would You Give A Five-Star Review on Yelp? -- Getting Your Hands Dirty with scikit-learn](http://nbviewer.jupyter.org/github/xun-tang/pyladies_jupyter_demo/blob/master/Predict_Review_Five_Star_Rating.ipynb), by [Xun Tang](https://www.linkedin.com/in/xuntang). Complimentary [slides](https://docs.google.com/presentation/d/1bfrXePztSa-yTP8n_qTdd9zazNS_tyJs1mG3fYItznI/edit).  

* [Geodemographic Segmentation Model](http://nbviewer.jupyter.org/github/filipacsr/DataScience/blob/master/GeodemographicSegmentationModel.ipynb), by [Filipa Rodrigues](https://www.linkedin.com/in/filipacrodrigues/)




### Neural networks

* [Neural Networks](http://nbviewer.ipython.org/github/masinoa/machine_learning/blob/master/04_Neural_Networks.ipynb), part of a collection on [machine learning](https://github.com/masinoa/machine_learning) by [Aaron Masino](https://github.com/masinoa).


### Computer vision 

* [SciPy and OpenCV as an interactive computing environment for computer vision](http://nbviewer.ipython.org/github/thsant/scipy4cv) by [Thiago Santos](http://ttsantos.net), a tutorial presented at [SIBGRAPI 2014](http://emap.fgv.br/sibgrapi-2014/tutorials.html).



## Natural Language Processing (NLP)

* [Workshop on text analysis](http://nbviewer.ipython.org/github/nealcaren/workshop_2014/tree/master/notebooks/) by [Neal Caren](http://nealcaren.web.unc.edu).

* [Detecting Algorithmically Generated Domains](http://nbviewer.ipython.org/github/ClickSecurity/data_hacking/blob/master/dga_detection/DGA_Domain_Detection.ipynb), part of the [Data Hacking](http://clicksecurity.github.io/data_hacking) collection on security-oriented data analysis with IPython & friends.

* [Mining the Social Web (2nd Edition)](https://github.com/ptwobrussell/Mining-the-Social-Web-2nd-Edition). A complete collection of notebooks accompanying [Matthew Russel's book](http://shop.oreilly.com/product/0636920030195.do) by O'Reilly.

* [Python Programming for the Humanities](http://fbkarsdorp.github.io/python-course/) by Folgert Karsdorp & Maarten van Gompel.

* [News Categorization using Multinomial Naive Bayes](http://nbviewer.jupyter.org/github/andressotov/News-Categorization-MNB/blob/master/News_Categorization_MNB%2010-oct-2017.ipynb) by Andres Soto Villaverde.

* [Using random cross-validation for news categorization](http://nbviewer.jupyter.org/github/andressotov/rnd_cross_valid/blob/master/Using%20random%20cross-validation%20for%20news%20categorization.ipynb) by Andres Soto Villaverde.



## Visualize it

* A [great matplotlib tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb), part of the fantastic [Lectures on Scientific Computing with Python](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/tree/master) by [J.R. Johansson](https://github.com/jrjohansson).

* [Plotting pitfalls](https://anaconda.org/jbednar/plotting_pitfalls/notebook): common problems when plotting large datasets, and how to avoid them. By James A. Bednar.

* [US Census data](https://anaconda.org/jbednar/census/notebook) and [NYC Taxi data](https://anaconda.org/jbednar/nyc_taxi/notebook) visualized using [datashader](https://github.com/bokeh/datashader).

* A [Notebook](http://nbviewer.ipython.org/github/plotly/python-user-guide/blob/master/s3_bubble-charts/s3_bubble-charts.ipynb) with an interactive Hans Rosling Gapminder bubble chart from [Plotly](https://plot.ly/api/Python). 

* [Data and visualization integration via web based resources](http://tw.rpi.edu/media/2013/09/25/a48/The_Perfect_Storm_1991.html). Using NetCDF, Matplotlib, IPython Parallel and ffmpeg to generate video animation from time series of gridded data. By Massimo Di Stefano.

* [21 Interactive, D3 Plots from matplotlib, ggplot for Python,
prettyplotlib, Stack Overflow, and seaborn](http://nbviewer.ipython.org/gist/msund/7ac1203ded66fe8134cc). 

* [Visualizing complex-valued functions with Matplotlib and Mayavi](http://nbviewer.ipython.org/github/empet/Math/blob/master/DomainColoring.ipynb), by [Emilia Petrisor](https://github.com/empet).

* [bqplot](https://github.com/bloomberg/bqplot) is a d3-based interactive visualization library built entirely on top of that `ipywidgets` infrastructure. Checkout the [pythonic recreation](https://github.com/bloomberg/bqplot/blob/master/examples/Applications/Wealth%20of%20Nations.ipynb) of Hans Rosling's [Wealth of Nations](http://www.ted.com/talks/hans_rosling_shows_the_best_stats_you_ve_ever_seen?language=en).

* [A D3 Viewer for Matplotlib Visualizations](http://jakevdp.github.io/blog/2013/12/19/a-d3-viewer-for-matplotlib/), different from above by not depending on Plot.ly account.

* [Bokeh is an interactive web visualization library for Python](http://nbviewer.jupyter.org/github/bokeh/bokeh-notebooks/blob/master/quickstart/quickstart.ipynb) (and other languages). It provides d3-like novel graphics, over large datasets, all without requiring any knowledge of Javascript. It also has a Matplotlib compatibility layer.

* [HoloViews](http://holoviews.org/Tutorials/Showcase.html) lets you construct visualizations very concisely in the notebook.

* [Winner of the 2014 E. Tufte Slope Graphs contest](http://nbviewer.ipython.org/gist/pascal-schetelat/8382651), by [Pascal Schetelat](https://github.com/pascal-schetelat).  The original [contest info on Tufte's site](http://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0003nk).

* [matta, d3.js-based visualizations in the IPython Notebook](http://nbviewer.ipython.org/github/carnby/matta/blob/master/examples/Basic%20Examples.ipynb), by [Eduardo Graells-Garrido](http://carnby.github.io/).

* [Clustergrammer Interactive Heatmap and DataFrame Viewer](http://nbviewer.jupyter.org/github/MaayanLab/clustergrammer-widget/blob/master/Running_clustergrammer_widget.ipynb) This Python notebook shows a simple example of how to visualize a matrix file and Pandas DataFrame as an interactive heatmap (built using D3.js) using the Jupyter Widget [Clustergrammer](http://clustergrammer.readthedocs.io/clustergrammer_widget.html) (see [paper](https://www.nature.com/articles/sdata2017151)).



## Programming and Computer Science

* [Numeric Computing is Fun](https://github.com/mikkokotila/jupyter4kids) A series of notebooks created to help educate aspiring computer programmers and data scientists of all ages with no previous programming experience.

* [Python for Developers](http://ricardoduarte.github.io/python-for-developers), a complete book on Python programming by [Ricardo Duarte](https://github.com/ricardoduarte). Note the book also exists [in Portuguese](http://ricardoduarte.github.io/python-para-desenvolvedores).

* [CS1001.py - Extended Introduction to Computer Science](https://github.com/yoavram/CS1001.py). Recitations from Tel-Aviv University introductory course to computer science, assembled as IPython notebooks by [Yoav Ram](http://www.yoavram.com/).

* [Exploratory Computing with Python](http://mbakker7.github.io/exploratory_computing_with_python/), a set of 15 Notebooks that cover exploratory computing, data analysis, and visualization. No prior programming knowledge required. Each Notebook includes a number of exercises (with answers) that should take less than 4 hours to complete. Developed by Mark Bakker for undergraduate engineering students at the Delft University of Technology.

* [Understanding evolutionary strategies and covariance matrix adaptation](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/blob/master/AEC.04%20-%20Evolutionary%20Strategies%20and%20Covariance%20Matrix%20Adaptation.ipynb), from the [Advanced Evolutionary Computation: Theory and Practice](http://nbviewer.ipython.org/github/lmarti/evolutionary-computation-course/tree/master/) course by [Luis Martí](http://lmarti.com).

* [Code Katas in Python](https://github.com/gudnm/codekatas), a collection of algorithmic and data structure exercises covering search and sorting algorithms, stacks, queues, linked lists, graphs, backtracking and greedy problems.

* [Algorithms in IPython notebooks](https://github.com/rasbt/algorithms_in_ipython_notebooks), by [Sebastian Raschka](https://github.com/rasbt)

* [Comparing the performance of Python compilers - Cython vs. Numba vs. Parakeet](_nbs/day4_2_cython_numba_parakeet.ipynb?create=1), by [Sebastian Raschka](https://github.com/rasbt)



## Scientific computing and data analysis with the SciPy Stack

### General topics in scientific computing

* [A Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/5920182), by Sandia's [Rick Muller](http://www.cs.sandia.gov/~rmuller).

* [A gentle introduction to scientific programming in Python, biased towards biologists](http://nbviewer.ipython.org/url/atwallab.cshl.edu/teaching/QBbootcamp3.ipynb), by [Mickey Atwal, Cold Spring Harbor Laboratory](http://atwallab.cshl.edu).

* [CythonGSL: a Cython interface for the GNU Scientific Library (GSL)](http://nbviewer.ipython.org/github/twiecki/CythonGSL/blob/master/examples/cython_gsl_ipythonnb.ipynb) ([Project repo](https://github.com/twiecki/CythonGSL), by Thomas Wiecki.

* [Introduction to numerical computing with numpy](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/numerical-slides.ipynb) by [Steve Phelps](http://sphelps.net).

* [Using Numba to speed up numerical codes](http://nbviewer.ipython.org/gist/3914904).  And another Numba example: [self-organizing maps](http://nbviewer.ipython.org/gist/3407544).

* [Numpy performance tricks](http://nbviewer.ipython.org/gist/4645217), and [blog post](http://cyrille.rossant.net/numpy-performance-tricks/), by [Cyrille Rossant](http://cyrille.rossant.net/).

* [IPython Parallel Push/Execute/Pull Demo](http://nbviewer.ipython.org/gist/3866987) by Justin Riley.

* [Understanding the design of the R "formula" objects](http://nbviewer.ipython.org/url/perrin.dynevor.org/exploring_r_formula.ipynb) by Matthew Brett.

* [Comparing different approaches to evolutionary simulations](http://nbviewer.ipython.org/url/www.slideviper.oquanta.info/test/simulation%20frameworks.ipynb). Also available [here](http://slideviewer.herokuapp.com/urls/github.com/yoavram/ipython-notebooks/raw/master/simulation%20frameworks.ipynb) to better visualization. The notebook was converted to a HTML presentation using an old nbconvert with the first developing implementation of `reveal` converter. By Yoav Ram.

* [The Traveling Salesperson Problem](http://nbviewer.jupyter.org/url/norvig.com/ipython/TSP.ipynb) by [Peter Norvig](http://norvig.com).

* [A git tutorial targeted at scientists](http://nbviewer.ipython.org/github/fperez/reprosw/blob/master/Version%20Control.ipynb) by Fernando Perez.

* [Interactive Curve-Fitting](http://nbviewer.ipython.org/gist/danielballan/1c2db3d4f2f7780cf52f) The `lmfit` package provides a widget-based interface to the curve-fitting algorithms in SciPy.

* [A visual guide to the Python Spark API for distributed computing](http://nbviewer.ipython.org/github/jkthompson/pyspark-pictures/blob/master/pyspark-pictures.ipynb) by Jeff Thompson

* [A tutorial on Map-Reduce programming with Apache Spark and Python](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/spark-mapreduce.ipynb) by [Steve Phelps](http://sphelps.net).

* [CodeCombat gridmancer solver](http://nbviewer.jupyter.org/github/Arn-O/py-gridmancer/blob/master/gridmancer.ipynb) by [Arn-O](https://github.com/Arn-O). This notebook explains how to improve a recursive tree search with an heuristic function and to find the minimum solution to the gridmancer.


### Social data

* [Survival Analysis](http://nbviewer.ipython.org/github/CamDavidsonPilon/lifelines/blob/master/docs/Survival%20Analysis%20intro.ipynb), an illustration of the [lifelines library](https://github.com/CamDavidsonPilon/lifelines), by [Cam Davidson Pilon](https://github.com/CamDavidsonPilon).

* A reconstruction of [Nate Silver's 538 model for the 2012 US Presidential Election](http://nbviewer.ipython.org/github/jseabold/538model/blob/master/silver_model.ipynb), by Skipper Seabold (complete [repo](https://github.com/jseabold/538model)).

* [Data about the Sandy Hook massacre in Newtown, Conneticut](http://nbviewer.ipython.org/url/www.brianckeegan.com/data/Shootings/Shootings.ipynb), which accompanies a more detailed [blog post on the subject](http://www.brianckeegan.com/2012/12/sandy-hook-school-massacre/). Here are the [notebook and accompanying data](http://www.brianckeegan.com/data/Shootings/Shootings.ipynb).  By Brian Keegan.

* More on [gun violence analysis with Wikipedia data](http://nbviewer.ipython.org/gist/4358066).

* [An analysis of the Gaza-Israel 2012 crisis](http://nbviewer.ipython.org/gist/4121857).

* [Ranking NFL Teams](http://nbviewer.ipython.org/github/seanjtaylor/NFLRanking/blob/master/NFL%20Rankings.ipynb). The [full repo](https://github.com/seanjtaylor/NFLRanking) also includes an explanatory slideshow. By Sean Taylor.

* [Automated processing of news media and generation of associated imagery](http://nbviewer.ipython.org/url/mhermans.net/files/tmp/demo_rdf_HLN.ipynb). 

* [An analysis of national school standardized test data in Colombia using Pandas](http://nbviewer.ipython.org/url/finiterank.com/saber/saber.ipynb) (in Spanish). By [Javier Moreno](http://finiterank.com).

* [Getting started with GDELT](http://nbviewer.ipython.org/github/dmasad/GDELT_Intro/blob/master/Getting_Started_with_GDELT.ipynb), by [David Masad](https://github.com/dmasad). [GDELT](http://eventdata.psu.edu/data.dir/GDELT.html) is a dataset containing more than 200-million geolocated events with global coverage for 1979 to the present.  Another GDELT example from David, that nicely [integrates mapping visualizations](http://nbviewer.ipython.org/github/dmasad/GDELT_Intro/blob/master/GDELT_Mapping.ipynb).

* [Titanic passengers, coal mining disasters, and vessel speed changes](http://nbviewer.ipython.org/gist/fonnesbeck/8495259), by [Christopher Fonnesbeck](http://biostat.mc.vanderbilt.edu/wiki/Main/ChrisFonnesbeck)

* A geographic analysis of [Indonesian conflicts in 2012](http://nbviewer.ipython.org/github/herrfz/gdelt/blob/master/indn_connection.ipynb) with GDELT, by [herrfz](https://github.com/herrfz).

* [Bioinformatic Approaches to the Computation of Poetic Meter](http://nbviewer.ipython.org/github/asp49/meter/blob/graph/Shared%20Horizons%20Presentation.ipynb), by [A. Sean Pue](https://github.com/asp49), [C. Titus Brown](https://github.com/ctb) and [Tracy Teal](https://github.com/tracyteal).

* Analyzing the [Vélib dataset from Paris](http://nbviewer.ipython.org/gist/5520933), by [Cyrille Rossant](https://github.com/rossant) (Vélib is Paris' [bicycle-sharing program](http://en.wikipedia.org/wiki/V%C3%A9lib')).

* [Using Python to see how the Times writes about men and women](http://nbviewer.ipython.org/gist/5105037), by [Neal Caren](https://twitter.com/HaphazardSoc).

* [Exploring graph properties of the Twitter stream with twython and NetworkX](http://nbviewer.ipython.org/gist/5681541/TwitterGraphs.ipynb), by [F. Perez](http://fperez.org) (complete [gist repo with utilities here](https://gist.github.com/fperez/5681541).)

* [How clean are San Francisco's restaurants?](http://nbviewer.ipython.org/github/Jay-Oh-eN/happy-healthy-hungry/blob/master/h3.ipynb), a data science tutorial that accompanies a [blog post](http://blog.zipfianacademy.com/post/57158627293/how-to-data-science-mapping-sf-restaurant-inspection) from [Zipfian Academy](http://zipfianacademy.com/).

* [NYT gender wage gap and US crime by state](http://nbviewer.ipython.org/github/plotly/IPython-plotly/blob/master/Bubble%20Chart%20Explorer.ipynb).

* [Predicting usage of the subway system in NYC](http://nbviewer.ipython.org/url/www.asimihsan.com/articles/Intro%20to%20Data%20Science%20-%20Final%20Project.ipynb), a [final project](http://blog.udacity.com/2014/05/intro-to-data-science-tools-to-ask.html) for the Udacity Intro to Data Science Course, by [Asim Ihsan](http://www.asimihsan.com).

* [An exploratory statistical analysis of the 2014 World Cup Final](http://nbviewer.ipython.org/github/rjtavares/football-crunching/blob/master/notebooks/an%20exploratory%20data%20analysis%20of%20the%20world%20cup%20final.ipynb), by [Ricardo Tavares](https://github.com/rjtavares).  Part of a [notebook collection on football (aka soccer) analysis](http://nbviewer.ipython.org/github/rjtavares/football-crunching/tree/master/).

* [San Francisco's Drug Geography](http://nbviewer.ipython.org/github/lmart999/GIS/blob/master/SF_GIS_Crime.ipynb), a GIS analysis of public crime data in SF, by [Lance Martin](https://github.com/lmart999).

* [Geographic Data Science](http://darribas.org/gds17/) is an entire course by [Dani Arribas-Bel](http://darribas.org) to learn to access, munge, and analyse spatial data on social phenomena.

* [Analysis and visualization of a public OKCupid profile dataset using Python and Pandas](http://nbviewer.jupyter.org/github/lalelale/profiles_analysis/blob/master/profiles.ipynb) by [Alessandro Giusti](http://www.idsia.ch/~giusti) includes many colorful data visualizations.


### Psychology and Neuroscience

* [Cue Combination with Neural Populations](http://nbviewer.ipython.org/github/wtadler/cue-combination-with-neurons/blob/master/neural_cue_combination.ipynb) by [Will Adler](http://www.wtadler.com). Intuition and simulation for the theory (Ma *et al.*, 2006) that through probabilistic population codes, neurons can perform optimal cue combination with simple linear operations. Demonstrates that variance in cortical activity, rather than impairing sensory systems, is an adaptive mechanism to encode uncertainty in sensory measurements.

* [Modeling psychophysical data with non-linear functions](http://nbviewer.ipython.org/github/arokem/teach_optimization/blob/master/optimization.ipynb) by Ariel Rokem.

* [Visualizing mathematical models of brain cell connections](http://nbviewer.ipython.org/github/jonasnick/ReceptiveFields/blob/master/receptiveFields.ipynb). The effect of convolution of different receptive field functions and natural images is examined.

* [Python for Vision Research](http://nbviewer.ipython.org/github/gestaltrevision/python_for_visres/blob/master/index.ipynb). A three-day crash course for vision researchers in programming with Python, building experiments with [PsychoPy](http://psychopy.org/) and [psychopy_ext](http://psychopy_ext.klab.lt/), learning the fMRI multi-voxel pattern analysis with [PyMVPA](http://www.pymvpa.org/), and understading image processing in Python.

* [Loading and visualizing fMRI data](http://nbviewer.ipython.org/github/GaelVaroquaux/nilearn_course/blob/master/rendered_notebooks/1_Introduction.ipynb), part of the [Functional connectivity with NiLearn course](https://github.com/GaelVaroquaux/nilearn_course) by [Gaël Varoquaux](http://gael-varoquaux.info).


### Physics, Chemistry and Biology

* [Writing A Genome Assembler with blasr and (I)Python](http://nbviewer.jupyter.org/github/cschin/Write_A_Genome_Assembler_With_IPython/blob/master/Write_An_Assembler.ipynb), by [Jason Chin](Jason Chin).

* [Multibody dynamics and control with Python](http://www.moorepants.info/blog/npendulum.html) and the [notebook file](http://nbviewer.ipython.org/github/gilbertgede/idetc-2013-paper/blob/master/n-pendulum-control.ipynb) by Jason K. Moore.

* [Manipulation and display of chemical structures](http://nbviewer.ipython.org/gist/4316433), by [Greg Landrum](https://github.com/greglandrum), using rdkit.

* [The sound of Hydrogen](http://nbviewer.ipython.org/github/Carreau/posts/blob/master/07-the-sound-of-hydrogen.ipynb), visualizing and listening to the quantum-mechanical spectrum of Hydrogen. By [Matthias Bussonnier](http://github.com/Carreau).

* Particle physics at the Large Hadron Collider (LHC):  using [ROOT in an LHCb masterclass](http://root.cern.ch/drupal/content/ipython-notebooks-and-root-0): [Notebook 1](http://nbviewer.ipython.org/github/mazurov/webfest2013/blob/master/notebooks/MasterClassD0-ex1.ipynb) and [Notebook 2](http://nbviewer.ipython.org/github/mazurov/webfest2013/blob/master/notebooks/MasterClassD0-ex2%2Cex3.ipynb) notebooks by Alexander Mazurov and Andrey Ustyuzhanin at CERN.

* [A Reaction-Diffusion Equation Solver in Python with Numpy](http://nbviewer.ipython.org/github/waltherg/notebooks/blob/master/2013-12-03-Crank_Nicolson.ipynb), a demonstration of how IPython notebooks can be used to discuss both the theory and implementation of numerical algorithms on one page, by [Georg Walther](https://github.com/waltherg).

* [Comparing different approaches to evolutionary simulations](http://nbviewer.ipython.org/url/www.slideviper.oquanta.info/test/simulation%20frameworks.ipynb). Also available [here](http://slideviewer.herokuapp.com/urls/github.com/yoavram/ipython-notebooks/raw/master/simulation%20frameworks.ipynb) to better visualization. The notebook was converted to a HTML presentation using an old nbconvert with the first developing implementation of `reveal` converter. By Yoav Ram.


### Economics and Finance

* [Replication of the highly-contentious analysis of economic growth by Reinhart and Rogoff](http://nbviewer.ipython.org/github/vincentarelbundock/Reinhart-Rogoff/blob/master/reinhart-rogoff.ipynb), by [Vincent Arel-Bundock](http://umich.edu/~varel), [full repo here](https://github.com/vincentarelbundock/Reinhart-Rogoff). This is based on the [widely-publicized critique of the original analysis done by Herndon, Ash, and Pollin](http://www.peri.umass.edu/236/hash/31e2ff374b6377b2ddec04deaa6388b1/publication/566).

* [fecon235 for Financial Economics](https://github.com/rsvp/fecon235) series of notebooks which examines time-series data for economics and finance. Easy API to freely access data from the Federal Reserve, SEC, CFTC, stock and futures exchanges. Thus research from older notebooks can be replicated, and updated using the most current data. For example, this notebook forecasts likely Fed policy for setting the [Fed Funds rate](https://git.io/fedfunds), but market sentiment across major asset classes is observable from the [CFTC Commitment of Traders Report](https://git.io/cotr). Major economics indicators are renormalized: for example, various measures of [inflation](https://git.io/infl), optionally with the forward-looking break-even rates derived from U.S. Treasury bonds. Other notebooks examine international markets: especially, gold and foreign exchange. 

* [Fixed Income: A Structured Bond- Interactive scenarios ](http://nbviewer.jupyter.org/github/MatsGustavsson/finance-jupyter/blob/2b5c1458b0e9b9c299fe25590566814e92287a1c/SequentialStructure.ipynb), Sequential repayment of a bond using interactive widgets and Python in Jupyter, by [Mats Gustavsson](https://github.com/MatsGustavsson).


### Earth science and geo-spatial data
* [Exploring seafloor habitats: geographic analysis using IPython Notebook with GRASS & R](http://nbviewer.ipython.org/gist/7598354). This embeds a slideshow and a Web Spinning Globe (Cesium) in the notebook.  By Massimo Di Stefano.

* [Geo-Spatial Data with IPython](http://nbviewer.ipython.org/github/mqlaql/geospatial-data/blob/master/Geospatial-Data-with-Python.ipynb). Tutorial by [Kelsey Jordahl](http://kjordahl.net/) from SciPy2013.

* [EarthPy](http://earthpy.org), a collection of IPython notebooks with a focus on Earth Sciences, from [whale tracks](http://earthpy.org/analyzing-whale-tracks.html) to the [flow of the Amazon](http://earthpy.org/earthpy-basemap-amazon.html).

* [Python for Geosciences](https://github.com/koldunovn/python_for_geosciences), a tutorial series aimed at the Earth Sciences community, by [Nikolay Koldunov](http://earthpy.org/author/nikolay-koldunov.html).

* [Find graffiti close to NY subway entrances](http://nbviewer.ipython.org/github/invisibleroads/crosscompute-tutorials/blob/master/computational-analysis/300%20Count%20graffiti%20sightings%20within%20100%20feet%20of%20a%20subway%20entrance.ipynb), one of a rich [collection of notebooks on large-scale data analysis](https://github.com/invisibleroads/crosscompute-tutorials), by [Roy Hyunjin Han](https://github.com/invisibleroads).

* [Logistic models of well switching in Bangladesh](http://nbviewer.ipython.org/github/carljv/Will_it_Python/blob/master/ARM/ch5/arsenic_wells_switching.ipynb), part of the ["Will it Python"](http://slendrmeans.wordpress.com/will-it-python) blog series ([repo](https://github.com/carljv/Will_it_Python)) on Machine Learning and data analysis in Python.  By Carl Vogel.

* [Estimated likelihood of observing a large earthquake on a continental low‐angle normal fault and implications for low‐angle normal fault activity](http://nbviewer.ipython.org/github/cossatot/lanf_earthquake_likelihood/blob/master/notebooks/lanf_manuscript_notebook.ipynb), an executable version of a paper by Richard Styron and Eric Hetland published in *Geophysical Research Letters*, on earthquake probabilities.

* [python4oceanographers](https://ocefpaf.github.io/python4oceanographers/), a blog demonstrating analyses in physical oceanography from [resource-demanding numerical computations with functions in compiled languages](https://ocefpaf.github.io/python4oceanographers/blog/2015/10/05/isosurfaces/) to specialized [tidal analysis](https://ocefpaf.github.io/python4oceanographers/blog/2015/02/16/utide/) to [visualization of various geo data using fancy things like interactive maps](https://ocefpaf.github.io/python4oceanographers/blog/2015/07/13/interactive_geo/).

* [Machinalis](http://www.machinalis.com/) has a [public repo](https://github.com/machinalis/satimg) with material support for geospatial-data processing related blog posts. It includes notebooks about [Object Based Image Analysis](http://nbviewer.jupyter.org/github/machinalis/satimg/blob/master/object_based_image_analysis.ipynb) and [irrigation circles detection](http://nbviewer.jupyter.org/github/machinalis/satimg/blob/master/Searching%20for%20aliens.ipynb).

* [seismo-live](http://seismo-live.org/) is a collection of live Jupyter notebooks for seismology. It includes a fairly large number of notebooks on how to solve the acoustic and elastic wave equation with various different numerical methods. Additionally it contains notebooks with an extensive introduction to data handling and signal processing in seismology, and notebooks tackling ambient seismic noise, rotational and glacial seismology, and more.


### Mathematics

* [Linear algebra with Cython](http://nbviewer.ipython.org/github/carljv/cython_testing/blob/master/cython_linalg.ipynb).  A tutorial that styles the notebook differently to show that you can produce high-quality typography online with the Notebook.  By Carl Vogel.

* [Exploring how smooth-looking functions can have very surprising derivatives even at low orders](http://nbviewer.ipython.org/url/finiterank.com/cuadernos/suavesylocas.ipynb), combining SymPy and matplotlib.  By [Javier Moreno](http://finiterank.com).

* [A Collection of Applied Mathematics and Machine Learning Tutorials](http://sayilarvekuramlar.blogspot.co.uk/2015/12/matematik-ders-notlari.html) (in Turkish). By Burak Bayramli.

* [Function minimization with iminuit](http://nbviewer.ipython.org/github/iminuit/iminuit/blob/master/tutorial/tutorial.ipynb), an introductory companion to their [hard core tutorial](http://nbviewer.ipython.org/github/iminuit/iminuit/blob/master/tutorial/hard-core-tutorial.ipynb). By the [iminuit project](http://iminuit.github.io/iminuit).

* [The Discrete Cosine Transform](http://nbviewer.ipython.org/url/cs.marlboro.edu/courses/spring2014/information/code/dct/dct.ipynb), a brief explanation and illustration of the math behind the DCT and its role in the JPEG image format, by [Jim Mahoney](http://cs.marlboro.edu).

* [Chebfun in Python](http://nbviewer.ipython.org/gist/6724986), a demo of [PyChebfun](https://github.com/cswiercz/pychebfun), by [Olivier Verdier](http://www.olivierverdier.com). PyChebfun is a pure-python implementation of the celebrated [Chebfun package by Battles and Trefethen](http://people.maths.ox.ac.uk/trefethen/publication/PDF/2004_107.pdf). 

* [The Matrix Exponential](http://nbviewer.ipython.org/github/sdrelton/matrix_function_notebooks/blob/master/TheMatrixExponential.ipynb), an introduction to the matrix exponential, its applications, and a list of available software in Python and MATLAB. By [Sam Relton](http://www.maths.manchester.ac.uk/~srelton/).

* [Fractals, complex numbers, and your imagination](http://nbviewer.ipython.org/github/cfangmeier/ipython_notebooks/blob/master/Imagination.ipynb), by [Caleb Fangmeier](https://github.com/cfangmeier).

* [A SymPy tutorial](http://nbviewer.ipython.org/url/www.inp.nsk.su/~grozin/python/sympy.ipynb), by [Andrey Grozin](http://www.inp.nsk.su/~grozin/).

* [Introduction to Mathematics with Python](https://github.com/drvinceknight/Python-Mathematics-Handbook), a collection of notebooks aimed at Mathematics with no/little Python knowledge. Notebooks can be selected to serve as resources for a workshop. By [Vince Knight](https://github.com/drvinceknight).


### Signal and Sound Processing

* [Simulation of Delta Sigma modulators in Python](http://nbviewer.ipython.org/github/ggventurini/python-deltasigma/blob/master/examples/dsdemo1.ipynb) with [deltasigma](https://github.com/ggventurini/python-deltasigma), Python port of of Richard Schreier's *excellent* [MATLAB Delta Sigma Toolbox](http://www.mathworks.com/matlabcentral/fileexchange/19-delta-sigma-toolbox), by [Giuseppe Venturini](https://github.com/ggventurini). Several demonstrative notebooks on the package [README](https://github.com/ggventurini/python-deltasigma/blob/master/README.md).

* [PyOracle: Automatic analysis of musical structure](http://nbviewer.ipython.org/urls/bitbucket.org/pucktronix/pyoracle/raw/d046b2bcf473503fa356094cfe4cff774d1aaefc/270D.ipynb), by [Greg Surges](http://gregsurges.com).

* [A Gallery of SciPy's Window Functions for quick visual inspection and comparison](http://nbviewer.ipython.org/urls/gist.githubusercontent.com/jaidevd/b7d865f7f4b237ab5181/raw/30bc8f998bf8f924b56b32ce10acce125656ed7c/scipy_window_gallery.ipynb)
 by [Jaidev Deshpande](http://twitter.com/jaidevd)

* [Poisson Image Editing | Seamless Cloning](http://nbviewer.jupyter.org/github/riddhishb/ipython-notebooks/blob/master/Poisson%20Editing/Seamless_Cloning.ipynb) by [Dhruv Ilesh Shah](https://github.com/PrieureDeSion) is a notebook that achieves Seamless Image Cloning by employing the Poisson Solver in the iterative form.

* [Blind Source Separation | Cocktail Party Problem](http://nbviewer.jupyter.org/github/riddhishb/ipython-notebooks/blob/master/Cocktail%20Party%20Problem/PCA_ICA_FOBI.ipynb) by [Dhruv Ilesh Shah](https://github.com/PrieureDeSion) & [Shashwat Shukla](https://github.com/ShashShukla) is a notebook that achieves blind source separation, on audio signals in an attempt to approach the Cocktail Party Prblem. The problem has been tackled in two different methods - the FOBI and fastICA.
 


## General Python Programming

* [Learning to code with Python](http://nbviewer.ipython.org/urls/bitbucket.org/amjoconn/watpy-learning-to-code-with-python/raw/3441274a54c7ff6ff3e37285aafcbbd8cb4774f0/notebook/Learn%20to%20Code%20with%20Python.ipynb), part of an [introduction to Python](https://bitbucket.org/amjoconn/watpy-learning-to-code-with-python/src) from the [Waterloo Python users group](http://watpy.ca/blog/post/learn-code-python-review-feb-2013).

* [Introduction to Python for Data Scientists](http://nbviewer.jupyter.org/github/phelps-sg/python-bigdata/blob/master/src/main/ipynb/intro-python.ipynb) by [Steve Phelps](http://sphelps.net) (part of a larger collection on [Data Science and Big Data](https://github.com/phelps-sg/python-bigdata)).

* [Python Descriptors Demystified](http://nbviewer.ipython.org/gist/ChrisBeaumont/5758381/descriptor_writeup.ipynb), an in-depth discussion of the descriptor protocol in Python, by [Chris Beaumont](http://chrisbeaumont.org).

* [A collection of not so obvious Python stuff you should know!](http://nbviewer.ipython.org/github/rasbt/python_reference/blob/master/tutorials/not_so_obvious_python_stuff.ipynb?create=1), by [Sebastian Raschka](https://github.com/rasbt).

* [Key differences between Python 2.7.x and Python 3.x](http://nbviewer.ipython.org/github/rasbt/python_reference/blob/master/tutorials/key_differences_between_python_2_and_3.ipynb), by [Sebastian Raschka](https://github.com/rasbt).

* [A beginner's guide to Python's namespaces, scope resolution, and the LEGB rule](http://nbviewer.ipython.org/github/rasbt/python_reference/blob/master/tutorials/scope_resolution_legb_rule.ipynb?create=1), by [Sebastian Raschka](https://github.com/rasbt).

* [Sorting CSV files using the Python csv module](http://nbviewer.ipython.org/github/rasbt/python_reference/blob/master/tutorials/sorting_csvs.ipynb), by [Sebastian Raschka](https://github.com/rasbt).

* Python 3 OOP series by [Leonardo Giordani](https://github.com/lgiordani): [Part 1: Objects and types](http://nbviewer.ipython.org/github/lgiordani/blog_source/blob/master/pelican/content/notebooks/Python_3_OOP_Part_1__Objects_and_types.ipynb), [Part 2: Classes and members](http://nbviewer.ipython.org/github/lgiordani/blog_source/blob/master/pelican/content/notebooks/Python_3_OOP_Part_2__Classes_and_members.ipynb), [Part 3: Delegation - composition and inheritance](http://nbviewer.ipython.org/github/lgiordani/blog_source/blob/master/pelican/content/notebooks/Python_3_OOP_Part_3__Delegation__composition_and_inheritance.ipynb), [Part 4: Polymorphism](http://nbviewer.ipython.org/github/lgiordani/blog_source/blob/master/pelican/content/notebooks/Python_3_OOP_Part_4__Polymorphism.ipynb), [Part 5: Metaclasses](http://nbviewer.ipython.org/github/lgiordani/blog_source/blob/master/pelican/content/notebooks/Python_3_OOP_Part_5__Metaclasses.ipynb), [Part 6: Abstract Base Classes](http://nbviewer.ipython.org/github/lgiordani/blog_source/blob/master/pelican/content/notebooks/Python_3_OOP_Part_6__Abstract_Base_Classes.ipynb)



### Mathematics, Physics, Chemistry, Biology

* A [single-atom laser model](http://nbviewer.ipython.org/github/jrjohansson/qutip-lectures/blob/master/Lecture-2B-Single-Atom-Lasing.ipynb). This is one of a complete set of [lectures on quantum mechanics and quantum optics using QuTiP](http://nbviewer.ipython.org/github/jrjohansson/qutip-lectures) by [J.R. Johansson](https://github.com/jrjohansson).

* [2-d rigid-body transformations](http://nbviewer.ipython.org/github/demotu/BMC/blob/master/notebooks/Transformation2D.ipynb). This is part of [Scientific Computing in Biomechanics and Motor Control](https://github.com/demotu/BMC), a complete collection of notebooks by [Marcos Duarte](https://github.com/demotu).

* Astrophysical simulations and analysis with [yt](http://yt-project.org): a collection of example notebooks on using various codes that yt interfaces with: [Enzo](http://nbviewer.ipython.org/url/hub.yt-project.org/notebooks/ac275ee8a462425c93b36e330e243705.ipynb), [Gadget](http://nbviewer.ipython.org/url/hub.yt-project.org/notebooks/e209c55b6aaa4a9ab12c55422bb3afdc.ipynb), [RAMSES](http://nbviewer.ipython.org/url/hub.yt-project.org/notebooks/9fe5b4bc68ce48d5aa665edbc4ec3aa3.ipynb), [PKDGrav](http://nbviewer.ipython.org/url/hub.yt-project.org/notebooks/9fe5b4bc68ce48d5aa665edbc4ec3aa3.ipynb) and [Gasoline](http://nbviewer.ipython.org/url/hub.yt-project.org/notebooks/9fe5b4bc68ce48d5aa665edbc4ec3aa3.ipynb). *Note:* the yt site currently throws an SSL warning, they seem to have an outdated or self-signed certificate.

* [Working with Reactions](http://nbviewer.ipython.org/gist/4316430), part of a set of tutorials on [cheminformatics and machine learning with the rdkit project](http://code.google.com/p/rdkit/wiki/UGM2012Tutorials), by Greg Landrum.

* [CFD Python: 12 steps to Navier-Stokes](http://lorenabarba.com/blog/cfd-python-12-steps-to-navier-stokes). A complete set of lectures on Computational Fluid Dynamics, from 1-d linear waves to full 2-d Navier-Stokes, by [Lorena Barba](http://lorenabarba.com).

* [Pytherm - Applied Thermodynamics](http://nbviewer.jupyter.org/github/iurisegtovich/PyTherm-applied-thermodynamics/blob/master/index.ipynb). Lectures on applied thermodynamics using Python and the SciPy ecosystem, by [ATOMS](http://atoms.peq.coppe.ufrj.br/).

* [AeroPython: Aerodynamics-Hydrodynamics with Python](https://github.com/barbagroup/AeroPython), a complete course taught at George Washington University by [Lorena Barba](http://lorenabarba.com).

* [Practical Numerical Methods with Python](https://github.com/numerical-mooc/numerical-mooc), a collection of learning modules (each consisting of several IPython Notebooks) for a course in numerical differential equations  taught  at George Washington University by [Lorena Barba](http://lorenabarba.com). Also offered as a "massive, open online course" (MOOC) on the [GW SEAS Open edX](http://openedx.seas.gwu.edu/courses/GW/MAE6286/2014_fall/about) platform.

* [pyuvvis: tools for explorative spectroscopy](https://github.com/hugadams/pyuvvis), spectroscopy library built for integration ipython notebooks, matplotlib and pandas.

* [HyperPython: a practical introduction to the solution of hyperbolic conservation laws](http://nbviewer.ipython.org/github/ketch/HyperPython/tree/master/), a course by [David Ketcheson](http://davidketcheson.info).

* [An Introduction to Applied Bioinformatics](http://readiab.org/): Interactive lessons in bioinformatics, by [Greg Caporaso](http://caporasolab.us).

* Colour science computations with [colour](https://github.com/colour-science/colour), a Python package implementing a comprehensive number of colour theory transformations and algorithms supported by a [dedicated collection of IPython Notebooks](http://nbviewer.ipython.org/github/colour-science/colour-ipython/blob/master/notebooks/colour.ipynb). More colour science related [IPython Notebooks](http://nbviewer.ipython.org/github/colour-science/colour-website/tree/master/ipython/) are available on [colour-science.org](http://colour-science.org/).

* The [notebooks](https://github.com/tiagoantao/bioinf-python/blob/master/notebooks/Welcome.ipynb) from the Book [Bioinformatics with Python Cookbook](http://www.amazon.com/Bioinformatics-Python-Cookbook-Tiago-Antao/dp/1782175113), covering several fields like Next-Generation Sequencing, Population Genetics, Phylogenetics, Genomics, Proteomics and Geo-referenced information.

* [Learning Population Genetics in an RNA world](http://nbviewer.jupyter.org/github/gocarli/RNA-Popgen-Notebook/blob/master/Population_Genetics.ipynb) is an interactive notebook that explains basic population genetics tools and techniques by building an in silico evolutionary model of RNA molecules.

* [An open RNA-Seq data analysis pipeline tutorial with an example of reprocessing data from a recent Zika virus study](http://nbviewer.jupyter.org/github/maayanlab/Zika-RNAseq-Pipeline/blob/master/Zika.ipynb). This notebook fully reproduces the research published in [this paper](https://f1000research.com/articles/5-1574/v1). The notebook uses mostly python but includes some bash and R as well and is relevant for researchers in bioinformatics and public health.  

* [Lung Cancer Post-Translational Modification and Gene Expression Regulation](http://nbviewer.jupyter.org/github/MaayanLab/CST_Lung_Cancer_Viz/blob/master/notebooks/CST_Data_Viz.ipynb?flush_cache=true). This Python notebook uses the Jupyter-widget [Clustergrammer-Widget](http://clustergrammer.readthedocs.io/clustergrammer_widget.html) to visualize hierarchical clustering of gene expression and post-translational modification data from 37 lung cancer cell lines as an interactive heatmap. The notebook is part of the research project from this [paper](https://www.nature.com/articles/sdata2017151). 



### Signal Processing

* [Sound Analysis with the Fourier Transform](https://github.com/calebmadrigal/FourierTalkOSCON). A set of IPython Notebooks by [Caleb Madrigal](http://calebmadrigal.com) to explain what the Fourier Transform is and how to use it for basic audio processing applications.

* [An introduction to Compressed Sensing](http://nbviewer.ipython.org/github/unpingco/Python-for-Signal-Processing/blob/master/Compressive_Sampling.ipynb), part of [Python for Signal Processing](http://nbviewer.ipython.org/github/unpingco/Python-for-Signal-Processing): an entire book (and [blog](http://python-for-signal-processing.blogspot.com)) on the subject by Jose Unpingco.
`ádasd`
* [Kalman and Bayesian Filters in Python](http://nbviewer.ipython.org/github/rlabbe/Kalman-and-Bayesian-Filters-in-Python/blob/master/table_of_contents.ipynb). A textbook and accompanying filtering library on the topic of Kalman filtering and other related Bayesian filtering techniques.

* [Classify human movements using Dynamic Time Warping & K Nearest Neighbors:](http://nbviewer.ipython.org/github/markdregan/K-Nearest-Neighbors-with-Dynamic-Time-Warping/blob/master/K_Nearest_Neighbor_Dynamic_Time_Warping.ipynb) Signals from a smart phone gyroscope and accelerometer are used to classify if the person is running, walking, sitting standing etc. This IPython notebook contains a python implementation of DTW and KNN algorithms along with explanations and a practical application.

* [Digital Signal Processing](https://github.com/spatialaudio/digital-signal-processing-lecture) A collection of notebooks that accompanies a masters course on the topic.

* [An introduction to openCV](https://github.com/handee/opencv-gettingstarted) An introduction course into using openCV for computer vision in python


### Engineering Education

* [Introduction to Chemical Engineering Analysis](http://jckantor.github.io/CBE20255/) by [Jeff Kantor](http://jckantor.github.io/). A collection of IPython notebooks illustrating topics in introductory chemical engineering analysis, including stoichiometry, generation-consumption analysis, mass and energy balances.

* [Sensors and Actuators](http://jckantor.github.io/CBE20255/) by [Andres Marrugo](http://andresmarrugo.net). A collection of Jupyter notebooks in the form of lecture notes and engineering calculations for the course IMTR 1713 Sensors and Actuators taught at the [Universidad Tecnológica de Bolívar](http://www.unitecnologica.edu.co/).



## Data-driven journalism

* [The Need for Openness in Data Journalism](http://nbviewer.ipython.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb), by [Brian Keegan](http://www.brianckeegan.com).

* [St. Louis County Segregation Analysis](https://github.com/BuzzFeedNews/2014-08-st-louis-county-segregation) , analysis for the article [The Ferguson Area Is Even More Segregated Than You Probably Guessed](http://www.buzzfeed.com/jsvine/the-ferguson-area-is-even-more-segregated-than-you-thought) by [Jeremy Singer-Vine](https://twitter.com/jsvine).

* [Size of thesis and dissertations in Quebec](https://github.com/jhroy/theses/blob/master/theses.ipynb), by [Jean-Hugues Roy](http://jhroy.ca) (in French).



## References

* [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks). Using jupyter notebook, python, and numpy to solve Board Game "Penguins on Ice".

