# Data Visualization notebooks

The collection is just my favorite list of useful notebooks and examples on data visualization topics.
Some of them are collected from other sources (including text description). References for the orignal sources here: [References](#References) 


# Table of Contents

1. [Visualize it](#visualize-it)
    * [Data visualization and plotting](#data-visualization-and-plotting)

1. [Visualize Machine Learning Algorithms](#visualize-machine-learning-algorithms )

1. [Data-driven journalism](#data-driven-journalism)

1. [References](#references)



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



## Visualization libs for Python 

* [matplotlib](http://matplotlib.org/) - a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* [seaborn](http://seaborn.pydata.org/) for statistical charts
* [altair](https://altair-viz.github.io/) Altair is a declarative statistical visualization library for Python, based on Vega-Lite
* [bokeh](https://bokeh.pydata.org/en/latest/) A Python interactive visualization library that targets modern web browsers for presentation.
* [plot.ly](https://plot.ly/python/) Plotly's Python graphing library makes interactive, publication-quality graphs online.

other interestitng libraries and tools to review 
* [Lightning](http://lightning-viz.org/documentation/#introduction) - Lightning is a framework for interactive data visualization, including a server, visualizations, and client libraries
* [HoloViews](http://holoviews.org/) - Stop plotting your data - annotate your data and let it visualize itself! 
* [Glue](http://www.glueviz.org/en/stable/python_guide/glue_from_python.html) - Multidimensional data exploration. Glue is a Python library to explore relationships within and among related datasets
* [VisPy](http://vispy.org/index.html) - VisPy is a Python library for interactive scientific visualization that is designed to be fast, scalable, and easy to use.
* [bqplot](https://github.com/bloomberg/bqplot) - Plotting library for IPython/Jupyter Notebooks 

## Data Visualization Framework (in progress...)

This chapter was inspired by [Data Visualization as a Driver for Visual Cognition Research](http://www.cs.ubc.ca/~tmm/talks/opam17/opam17.pdf) 
by [Tamara Munzner](http://www.cs.ubc.ca/~tmm/) and other [Tamara Munzner: Talks](http://www.cs.ubc.ca/~tmm/talks.html#opam17) 

### What is purpose? (visualization domain)

What is the purpose of data analysis? These notes are for data scientists who work with data for various purposes.
What purposes do the have for data visualization? 
- confirm expectations regarding the patterns in data
- explore new patterns, even unexpected 
- test hypotheses 


### What is data? (TBD)
What is data about? What types of data? And what visualization channels are appropriate? 


### Tasks (why do we need visualization?)

   * descriptive analysis 
       * discover distribution
       * discover central tendency
       * discover dispersion
       * discover bivariate distribution (via scatterplots)
       * build cross-tabulations and contingency tables 

        
   * exploratory data analysis (EDA)
       * compare trends
       * locate outliers
       * browse topology
       * compare shapes  
       * explore hypotheses on data relationships 
       * explore new patterns
       
### Means and tools (how to do reach our goals?) (TBD)

   * Encoding 
        * Express 
        * Separate
        * Order 
        * Align
   * Map 
        * Color 
        * Size, angle
        * Shape 
        * Motion
   * Manipulate  
        * Change 
        * Select
        * Navigte  
   * Facet 
        * Juxtapose 
        * Partition
        * Superimpose  
   * Reduce  
        * Filter 
        * Aggregate
        * Embed  


## Visualization techniques 

### Histograms 

* [What's so hard about histograms?](http://tinlizzie.org/histograms/). A step by step guide to using histograms lots of data visualizations


## t-SNE

* [How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/). Explore how it behaves in simple cases, we can learn to use it more effectively.



## Visualize Math and Machine Learning Algorithms 

* [A visual introduction to machine learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/). Visualisation app for applying Machine Learning machine learning to distinguish homes in New York from homes in San Francisco.

* [An Introduction to Machine Learning Theory and Its Applications: A Visual Tutorial with Examples](https://www.toptal.com/machine-learning/machine-learning-theory-an-introductory-primer). This tutorial introduces the basics of Machine Learning theory, laying down the common themes and concepts, making it easy to follow the logic and get comfortable with the topic

* [Why Momentum Really Works](https://distill.pub/2017/momentum/). A popular story about momentum: gradient descent is a man walking down a hill

* [Visualizing Algorithms](https://bost.ocks.org/mike/algorithms/). To visualize an algorithm, we don’t merely fit data to a chart; there is no primary dataset. Instead there are logical rules that describe behavior. 

* [Explained Visually](http://setosa.io/ev/). Explained Visually (EV) is an experiment in making hard ideas intuitive inspired the work of Bret Victor's Explorable Explanations.




### Visualize Neural Networks

* [TensorFlow playgraund](http://playground.tensorflow.org). Deep playground is an interactive visualization of neural networks, written in typescript using d3.js.

* [Four Experiments in Handwriting with a Neural Network](https://distill.pub/2016/handwriting/). Let’s start with generating new strokes based on your handwriting input.

* [Deconvolution and Checkerboard Artifacts](https://distill.pub/2016/deconv-checkerboard/). What’s going on in Neural Networks?

* [Attention and Augmented Recurrent Neural Networks](https://distill.pub/2016/augmented-rnns/). Look inside of the recurrent neural networks (RNN) 

* [Feature Visualization](https://distill.pub/2017/feature-visualization/). Feature visualization allows us to see how GoogLeNet, trained on the ImageNet dataset, builds up its understanding of images over many layers.

* [Visualizing Representations: Deep Learning and Human Beings](http://colah.github.io/posts/2015-01-Visualizing-Representations/). Visual representation on the internal operations of deep neural networks with text. 





## Data-driven journalism

* [The Need for Openness in Data Journalism](http://nbviewer.ipython.org/github/brianckeegan/Bechdel/blob/master/Bechdel_test.ipynb), by [Brian Keegan](http://www.brianckeegan.com).

* [St. Louis County Segregation Analysis](https://github.com/BuzzFeedNews/2014-08-st-louis-county-segregation) , analysis for the article [The Ferguson Area Is Even More Segregated Than You Probably Guessed](http://www.buzzfeed.com/jsvine/the-ferguson-area-is-even-more-segregated-than-you-thought) by [Jeremy Singer-Vine](https://twitter.com/jsvine).

* [Size of thesis and dissertations in Quebec](https://github.com/jhroy/theses/blob/master/theses.ipynb), by [Jean-Hugues Roy](http://jhroy.ca) (in French).



## Media for Thinking the Unthinkable

* [Media for Thinking the Unthinkable](http://worrydream.com/MediaForThinkingTheUnthinkable/), by Bret Victor.

* [Mike Bostock works](https://bost.ocks.org/mike/), by Mike Bostock.





## References gelleries and projects 

* [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks). Using jupyter notebook, python, and numpy to solve Board Game "Penguins on Ice".

* [A gellery of concept visualization](https://conceptviz.github.io/#/e30=). The Gallery of Concept Visualization features projects which use pictures to communicate complex and difficult ideas, the same way data visualizations use pictures to make sense of data.

* [Wolfram Demonstrations Project](http://demonstrations.wolfram.com/). Wolfram Demonstrations Project is an open-code resource that uses dynamic computation to illuminate concepts in science, technology, mathematics, art, finance, and a remarkable range of other fields.

* [Explorable Explanations](http://explorabl.es/), a hub for learning through play!

* [Big Picture Group](https://research.google.com/bigpicture/). We explore how information visualization can make complex data accessible, useful, and even fun

* [Text Visualization Browser](http://textvis.lnu.se/), A Visual Survey of Text Visualization Techniques