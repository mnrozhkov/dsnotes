# Reproducible Data Science 

Reproducibility is an important aspect in Data Science. These notes focus tools and technigques on how to make data science and machine learning flexible, testable and reproducible 

Some of them are collected from other sources (including text description). References for the orignal sources here: [References](#References) 


# Table of Contents

1. [What is Reproducible Data Science?](#what-is-reproducible-data-science)


1. [Tools and techniques](#tools-and-techniques)
    * [Reproducible Data Analysis in Jupyter](#reproducible-data-analysis-in-jupyter)

    
1. [Reproducible academic publications](#reproducible-academic-publications)

1. [References](#references)



## What is Reproducible Data Science?



## Tools and techniques

### Reproducible Data Analysis in Jupyter

* [Useful tools and techniques for Data Science](https://jakevdp.github.io/blog/2017/03/03/reproducible-data-analysis-in-jupyter/) by [Jake VanderPlas](https://jakevdp.github.io/pages/about.html) 



## Reproducible academic publications

This section contains academic papers that have been published in the peer-reviewed literature or pre-print sites such as the [ArXiv](http://arxiv.org) that include one or more notebooks that enable (even if only partially) readers to reproduce the results of the publication.  If you include a publication here, please link to the journal article as well as providing the nbviewer notebook link (and any other relevant resources associated with the paper).

* [Discovery of Gravitational Waves by the LIGO collaboration](https://losc.ligo.org/tutorials). That page, from the LIGO Open Science Center, contains multiple notebooks for various datasets corresponding to different events; [this binder](https://github.com/minrk/ligo-binder) lets you run the code right away. More details on the [GW150914](https://losc.ligo.org/events/GW150914) event as well as the original [main Physical Review Letters paper, "Observation of Gravitational Waves from a Binary Black Hole Merger"](http://journals.aps.org/prl/abstract/10.1103/PhysRevLett.116.061102).

* [Characterizing Strain Variation in Engineered E. coli Using a Multi-Omics-Based Workflow](http://www.cell.com/cell-systems/fulltext/S2405-4712(16)30112-0), by Brunk et al. 

* [Predicting Coronal Mass Ejections Using Machine Learning Methods](http://dx.doi.org/10.3847/0004-637X/821/2/127) by Monica Bobra and Stathis Ilonidis (Astrophysical Journal, 2016). An [IPython notebook](http://nbviewer.jupyter.org/github/mbobra/machine-learning-with-solar-data/blob/master/cme_svm.ipynb), which reproduces all the results, has been permanently deposited in the [Stanford Digital Repository](https://purl.stanford.edu/wt605kh4712).

* [The Paper of the Future](https://dx.doi.org/10.22541/au.148769949.92783646) by Alyssa Goodman et al. (Authorea Preprint, 2017). This article explains and shows with demonstrations how scholarly "papers" can morph into long-lasting rich records of scientific discourse, enriched with deep data and code linkages, interactive figures, audio, video, and commenting. It includes an interactive d3.js visualization and has an astronomical data figure with an IPYthon Notebook "behind" it.

* [Reply to 'Influence of cosmic ray variability on the monsoon rainfall and temperature': a false-positive in the field of solar-terrestrial research](http://arxiv.org/abs/1502.00505) by [Benjamin Laken](http://www.benlaken.com), 2015. Reviewed article will appear in JASTP. The [IPython notebook](http://nbviewer.ipython.org/github/benlaken/Comment_BadruddinAslam2014/blob/master/Monsoon_analysis.ipynb) reproduces the full analysis and figures exactly as they appear in the article, and is available on Github: link via [figshare](http://figshare.com/articles/Comment_on_Badruddin_amp_Aslam_2014_/1299413).

* [An open RNA-Seq data analysis pipeline tutorial with an example of reprocessing data from a recent Zika virus study](http://dx.doi.org/10.12688/f1000research.9110.1), by [Zichen Wang](http://wangz10.github.io/) and [Avi Ma'ayan](http://www.mssm.edu/labs/maayan). (F1000Research 2016, 5:1574). An [IPython notebook](http://nbviewer.jupyter.org/github/maayanlab/Zika-RNAseq-Pipeline/blob/master/Zika.ipynb) was used to perform the proposed RNA-Seq pipeline using public gene expression data of human cells after Zika virus infection. The computational pipeline is also version controlled and Dockerized available [here](https://github.com/MaayanLab/Zika-RNAseq-Pipeline).

* [The probability of improvement in Fisher's geometric model: a probabilistic approach](http://dx.doi.org/10.1016/j.tpb.2014.10.004), by [Yoav Ram](http://www.yoavram.com/) and [Lilach Hadany](https://sites.google.com/site/hadanylab/). (Theoretical Population Biology, 2014). An [IPython notebook](http://nbviewer.ipython.org/url/www.sciencedirect.com/science/MiamiMultiMediaURL/1-s2.0-S0040580914000811/1-s2.0-S0040580914000811-mmc1.txt/272364/FULL/S0040580914000811/471cf02085a52c248dc76ae65ad4409d/mmc1.txt), allowing figure reproduction, was deposited as a [supplementry file](http://www.sciencedirect.com/science/MiamiMultiMediaURL/1-s2.0-S0040580914000811/1-s2.0-S0040580914000811-mmc1.txt/272364/FULL/S0040580914000811/471cf02085a52c248dc76ae65ad4409d/mmc1.txt).

* [Stress-induced mutagenesis and complex adaptation](http://rspb.royalsocietypublishing.org/content/281/1792/20141025.abstract), by [Yoav Ram](http://www.yoavram.com/) and [Lilach Hadany](https://sites.google.com/site/hadanylab/) (Proceedings B, 2014). An [IPython notebook](https://github.com/yoavram/ruggedsim/blob/master/manuscript/supplementry.ipynb), allowing figures reproduction, was deposited as a [supplementry file](http://rspb.royalsocietypublishing.org/content/suppl/2014/08/19/rspb.2014.1025.DC1).

* [Automatic segmentation of odor maps in the mouse olfactory bulb using regularized non-negative matrix factorization](http://www.sciencedirect.com/science/article/pii/S1053811914003103), by J. Soelter et al. (Neuroimage 2014, Open Access). The [notebook](http://nbviewer.ipython.org/github/jansoe/FUImaging/blob/master/examples/IOSsegmentation/regNMF.ipynb) allows to reproduce most figures from the paper and provides a deeper look at the data. The [full code repository](https://github.com/jansoe/FUImaging/tree/Neuroimage2014) is also available.

* [Multi-tiered genomic analysis of head and neck cancer ties TP53 mutation to 3p loss, by A. Gross et al. (Nature Genetics 2014)](http://www.nature.com/ng/journal/vaop/ncurrent/full/ng.3051.html). The [full collection of notebooks to replicate the results](https://github.com/theandygross/TCGA/tree/master/Analysis_Notebooks#guide-to-running). 

* [Dog and human inflammatory bowel disease rely on overlapping yet distinct dysbiosis networks, by Vázquez-Baeza et al. (Nature microbiology 2016)](http://www.nature.com/articles/nmicrobiol2016177). The [full collection of notebooks to replicate the results](https://github.com/ElDeveloper/dogs).

* [powerlaw: a Python package for analysis of heavy-tailed distributions, by J. Alstott et al.](https://code.google.com/p/powerlaw/). [Notebook of examples in manuscript](http://nbviewer.ipython.org/gist/19fcdd6a4ba400ce8de2), [ArXiv link](http://arxiv.org/abs/1305.0215) and [project repository](https://github.com/jeffalstott/powerlaw).

* [Collaborative cloud-enabled tools allow rapid, reproducible biological insights, by B. Ragan-Kelley et al.](http://www.nature.com/ismej/journal/v7/n3/full/ismej2012123a.html). The [main notebook](http://nbviewer.ipython.org/gist/3693491/cloud_demo_complete.ipynb), the [full collection of related notebooks](http://nbviewer.ipython.org/gist/3693491) and the [companion site](http://qiime.org/home_static/nih-cloud-apr2012) with the Amazon AMI information for reproducing the full paper.

* [A Reference-Free Algorithm for Computational Normalization of Shotgun Sequencing Data, by C.T. Brown et al.](http://ged.msu.edu/papers/2012-diginorm). [Full notebook](http://nbviewer.ipython.org/urls/github.com/ged-lab/2012-paper-diginorm/raw/master/notebook/diginorm.ipynb), [ArXiv link](http://arxiv.org/abs/1203.4802) and [project repository](https://github.com/ged-lab/2012-paper-diginorm).

* [The kinematics of the Local Group in a cosmological context](http://arxiv.org/abs/1303.2690) by [J.E. Forero-Romero et al.](http://wwwprof.uniandes.edu.co/~je.forero/). The [Full notebook](http://nbviewer.ipython.org/github/forero/LG_Kinematics/blob/master/code/main_analysis.ipynb) and also all the data in a [github repo](https://github.com/forero/LG_Kinematics).

* [Warming Ocean Threatens Sea Life](http://www.scientificamerican.com/article.cfm?id=warming-ocean-threatens-sea-life), an article in Scientific American [backed by a notebook for its main plot](http://nbviewer.ipython.org/github/robertodealmeida/notebooks/blob/master/scientific_american/Scientific%20American%20graph.ipynb). By [Roberto de Almeida](https://github.com/robertodealmeida) from [MarinExplore](https://marinexplore.com).

* [Extrapolating Weak Selection in Evolutionary Games](http://nbviewer.ipython.org/github/juliangarcia/ews/blob/master/notebook.ipynb), by Wu, García, Hauert and Traulsen. [PLOS Comp Bio paper](http://www.ploscompbiol.org/article/info%3Adoi%2F10.1371%2Fjournal.pcbi.1003381) and [Figshare link](http://figshare.com/articles/Extrapolating_weak_selection_in_evolutionary_games_source_code/814470).

* [Using neural networks to estimate redshift distributions. An application to CFHTLenS](http://nbviewer.ipython.org/urls/bitbucket.org/christopher_bonnett/nn_notebook/raw/5e69b55193a229cb2076a2f18e43b45c56e317e0/T-800.ipynb)
by Christopher Bonnett [paper](http://arxiv.org/abs/1312.1287)(submitted to MNRAS) 

* [Mechanisms for stable, robust, and adaptive development of orientation maps in the primary visual cortex](http://dx.doi.org/10.1523/JNEUROSCI.1037-13.2013) by Jean-Luc R. Stevens, Judith S. Law, Jan Antolik, and James A. Bednar. Journal of Neuroscience, 33:15747-15766, 2013. [Notebook1]
(https://ioam.github.io/topographica/_static/gcal_notebook.html), [Notebook2](https://ioam.github.io/topographica/_static/stevens_jn13_notebook.html).

* [Accelerated Randomized Benchmarking](http://nbviewer.ipython.org/github/cgranade/accelerated-randomized-benchmarking/blob/master/src/model_testing.ipynb), by [Christopher Granade](http://www.cgranade.com/), [Christopher Ferrie](https://sites.google.com/site/csferrie/) and D. G. Cory. [New Journal of Physics **17** 013042 (2015)](http://iopscience.iop.org/article/10.1088/1367-2630/17/1/013042/meta;jsessionid=1F48CDD7C7D7849B0777C495ED1551CC.c1), [arXiv](http://arxiv.org/abs/1404.5275), [GitHub repo](https://github.com/cgranade/accelerated-randomized-benchmarking).

* [Dynamics and associations of microbial community types across the human body](http://dx.doi.org/10.1038/nature13178), by Tao Ding & Patrick D. Schloss. [Notebook replicating results](http://nbviewer.ipython.org/gist/pschloss/9815766/notebook.ipynb).

* [Variations in submarine channel sinuosity as a function of latitude and slope](http://nbviewer.ipython.org/gist/zsylvester/6040d0015b9b907bc788), by Sylvester, Z., Pirmez, C., Cantelli, A., & Jobe, Z. R.

* [Frontoparietal representations of task context support the flexible control of goal directed cognition](http://www.jneurosci.org/content/34/32/10743.short), by M.L. Waskom, D. Kumaran, A.M. Gordon, J. Rissman, & A.D. Wagner. [Github repository](https://github.com/WagnerLabPapers/Waskom_JNeurosci_2014) | [Main notebook](http://nbviewer.ipython.org/github/WagnerLabPapers/Waskom_JNeurosci_2014/blob/master/Behavioral_and_Decoding_Analyses.ipynb)

* [pyparty: Intuitive Particle Processing in Python](http://openresearchsoftware.metajnl.com/article/view/jors.bh), Adam Hughes [Notebook to Generate the Published Figures](http://nbviewer.ipython.org/github/hugadams/pyparty/blob/master/examples/Notebooks/JORS_data.ipynb?create=1) | Also, check out the [pyparty tutorial notebooks](https://github.com/hugadams/pyparty).

* [Indication of family-specific DNA methylation patterns in developing oysters](http://biorxiv.org/content/early/2014/12/16/012831), Claire E. Olson, Steven B. Roberts
doi: http://dx.doi.org/10.1101/012831. [Notebook to generate results in the paper](http://nbviewer.ipython.org/github/che625/olson-ms-nb/blob/master/BiGo_dev.ipynb).

* [Parallel Prefix Polymorphism Permits Parallelization, Presentation & Proof](http://conferences.computer.org/hptcdl/2014/papers/7020a047.pdf), [Jiahao Chen](http://jiahao.github.io) and [Alan Edelman](http://www-math.mit.edu/~edelman/), HPTCDL'14. [Website](http://jiahao.github.io/parallel-prefix) and [notebook](https://github.com/jiahao/ijulia-notebooks/blob/master/2014-08-06-parallel-prefix.ipynb)

* [Transcriptome Sequencing Reveals Potential Mechanism of Cryptic 3’ Splice Site Selection in *SF3B1*-mutated Cancers](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004105) by [Christopher DeBoever](http://cdeboever3.github.io/) et al. There are several [notebooks](https://github.com/cdeboever3/deboever-sf3b1-2015/tree/master/notebooks) to replicate results and make figures.

* [A Workflow for Characterizing Nanoparticle Monolayers for Biosensors: Machine Learning on Real and Artificial SEM Images](https://peerj.com/preprints/671/), Adam Hughes, Zhaowen Liu, Maryam Raftari, Mark. E Reeves.  Notebooks are linked in Table 1 in the text.

* [AtomPy: An Open Atomic Data Curation Environment for Astrophysical Applications](http://www.mdpi.com/2218-2004/2/2/123), by C. Mendoza, J. Boswell, D. Ajoku, M. Bautista.

* [Visualizing 4-Dimensional Asteroids](http://blogs.scientificamerican.com/sa-visual/2014/09/16/visualizing-4-dimensional-asteroids/), in Scientific American (by Jake VanderPlas)

* [Challenges and opportunities in understanding microbial communities with metagenome assembly](http://journal.frontiersin.org/article/10.3389/fmicb.2015.00678/abstract), [accompanied by IPython Notebook tutorial](http://nbviewer.ipython.org/github/germs-lab/frontiers-review-2015/blob/master/frontiers-nb-2015.ipynb), by [Adina Howe](http://germslab.org) and  Patrick Chain.

* [Structure of a shear-line polar low](http://onlinelibrary.wiley.com/doi/10.1002/qj.2911/abstract) (2016) by [Sergeev, D. E.](https://dennissergeev.github.io/), [Renfrew, I. A.](https://archive.uea.ac.uk/~e046/home.htm), Spengler, T. and Dorling, S. R. *Q.J.R. Meteorol. Soc.* doi:10.1002/qj.2911. Accompanied by [Notebooks to generate the published figures](https://github.com/dennissergeev/structure-of-a-shear-line-polar-low-notebooks).

* [Detecting High-Order Epistasis in Nonlinear Genotype-Phenotype Maps](http://www.genetics.org/content/205/3/1079) by [Zachary R. Sailer](https://github.com/Zsailer) and [Michael J. Harms](https://github.com/harmsm) published in *Genetics*, March 2017 . All figures can be reproduced by the set of notebooks in [this Github repo](https://github.com/harmslab/notebooks-nonlinear-high-order-epistasis). 

* [Summary Analysis of the 2017 GitHub Open Source Survey](https://osf.io/preprints/socarxiv/qps53/) by [Stuart Geiger](https://github.com/staeiou). Preprint in *SocArXiv*, June 2017. doi:10.17605/OSF.IO/ENRQ5. Paper is derived from a notebook converted to LaTeX with nbconvert. Notebook and materials at: [OSF](https://osf.io/enrq5/), [GitHub](https://github.com/staeiou/github-survey-analysis), [nbviewer](https://nbviewer.jupyter.org/github/staeiou/github-survey-analysis/blob/master/github-survey-descriptive-stats.ipynb)

* [The weirdest SDSS galaxies: results from an outlier detection algorithm](https://arxiv.org/abs/1611.07526), by [D. Baron](https://github.com/dalya) and D. Poznanski. [Notebooks to replicate](https://github.com/dalya/WeirdestGalaxies).

* [Clustergrammer, a web-based heatmap visualization and analysis tool for high-dimensional biological data](https://www.nature.com/articles/sdata2017151), by [Nicolas Fernandez](https://github.com/cornhundred) et al. Notebooks: [Fig. 3](http://nbviewer.jupyter.org/github/MaayanLab/CST_Lung_Cancer_Viz/blob/master/notebooks/CST_Data_Viz.ipynb), [Fig. 4](http://nbviewer.jupyter.org/github/MaayanLab/Cytof_Plasma_PMA/blob/master/notebooks/Compare_Cell-Type_Distribution_PMA_Treatment.ipynb), [Fig. 5](http://nbviewer.jupyter.org/github/MaayanLab/CCLE_Clustergrammer/blob/master/notebooks/Clustergrammer_CCLE_Notebook.ipynb)




## References

* [A gallery of interesting Jupyter Notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks). Using jupyter notebook, python, and numpy to solve Board Game "Penguins on Ice".
