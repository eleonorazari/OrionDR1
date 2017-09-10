# OrionDR1
Notebooks and queries used for the Orion paper.

Unfortunately the data files are too big to be uploaded, however the queries (see Queries.txt) 
can be used to retrieve them from the Archive.

The notebook titled KDEs is the collection of the scripts used to produce Fig. 4, 6, 8, 9, and 15.
Note that for Fig. 15, you need to install this package: http://dustmaps.readthedocs.io/en/latest/index.html.

The notebook titled unsharpMasking was used to make Fig. 7. 

The title of the notebook fig3 and fig5 is quite explicative. Fig 3. shows the sources with small proper motions
divided in parallax intervals. Fig. 5 shows the KDE of the parallax distribution of the sources with $2 < \varpi < 3.5$, and of the sources within the TGAS  density enhancements. Here I also compute the median of the KDEs after bootstrapping and the 16th and 84th percentiles.

bayesIsoFit_prlxConst is the notebook I used to a) perform the Bayesian Isochrone Fit with the procedure explained in Jorgensen and Lindegren (2005) b) make the age maps to study the age ranking of the different groups.

In the paper Appendix it is also described how to implement a uniform parallax prior. See notebook bayesIsoFit_prlxPrior.

Finally, everything I have done with PanStarrs is in the notebook with the same name.


