# cytoflow-examples
Example data sets, workflows and IPython notebooks.  These are not distributed
with `cytoflow` by default; you can download them at

https://github.com/bpteague/cytoflow-examples

Each subdirectory has a set of data files and an example Jupyter python 
notebook; in the future, I look to expand these to include example sessions
in the point-and-click interface, too.

Current examples include:

* **kiani/**
This example reproduces Figure 2, part (a), from [Kiani et al, Nature Methods 11: 723 (2014)](http://www.nature.com/nmeth/journal/v11/n7/full/nmeth.2969.html).  It demonstrates quantitative flow 
cytometry to characterize a transcriptional cascade using Cas9.  This is a 
non-trivial analysis using real, published data.

* **tasbe/**
A demonstration using `cytoflow` for calibrated flow cytometry, following
the TASBE method outlined in [Beal et al](http://dspace.mit.edu/handle/1721.1/69973) 
and its application in [Davidsohn et al.](http://pubs.acs.org/doi/abs/10.1021/sb500263b).