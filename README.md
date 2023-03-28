# Energy data analysis through statistical processes

This repository contains two case-study of statistical data analytics on energy data developed for the Ph.D. course of *Statistical data processing* 2022/23 held at the Politecnico di Torino.

The teachers involved are:
* Prof. Marco Piras ([Link](https://www.polito.it/en/staff?p=marco.piras))
* Prof. Paolo Dabove ([Link](https://www.polito.it/personale?p=paolo.dabove))
* Ph.D. Eng. Vincenzo di Pietra ([Link](https://www.polito.it/personale?p=vincenzo.dipietra))

The reports carried out from the analysis have been developed using [RMarkdown](https://rmarkdown.rstudio.com), a format for writing reproducible, dynamic reports with R. The format used is HTML documents, in order to obtain interactive and dynamic visualizations.

The two case-study analyzed are:
* Report 1 - **Multiple linear regression for energy data**: a regression analysis on a heating season dataset for a building has been performed, improving the accuracy of the model through the identification of outliers employing the Cook's distance.
* Report 2 - **High dimensional clustering for Energy Performance Certificates (EPCs)**: a Principal Component Analysis (PCA) coupled with K-means clustering was investigated in order to group buildings with similar attributes in the domain of EPCs. Greater attention was given to the interpretability phase, where clustering results were explained through the representation of variable distributions.

## Getting started
The [renv](https://rstudio.github.io/renv/articles/renv.html) package has been employed in order to align users to the same dependencies.
The step needed to clone and run the repository are:

* Open R console and run
``` r
install.packages("devtools")
devtools::install_github("Giudice7/Statistical_data_processing")
```

* To obtain the project library on the local machine, call
``` r
renv::restore()
```

Now the project should be active and ready to be run or modified locally.

## Author

* Rocco Giudice, *Ph.D. student* at Politecnico di Torino, [BAEDA Lab.](http://www.baeda.polito.it/)

## References

* Giacomo Buscemi, Marco Savino Piscitelli, Alfonso Capozzoli, Analysis of energy performance certificates of buildings through artificial intelligence processes, Politecnico di Torino, 2021.
* E. Di Corso, T. Cerquitelli, M. S. Piscitelli and A. Capozzoli, "Exploring Energy Certificates of Buildings through Unsupervised Data Mining Techniques," 2017 IEEE International Conference on Internet of Things (iThings) and IEEE Green Computing and Communications (GreenCom) and IEEE Cyber, Physical and Social Computing (CPSCom) and IEEE Smart Data (SmartData), Exeter, UK, 2017, pp. 991-998, doi: 10.1109/iThings-GreenCom-CPSCom-SmartData.2017.152.
* Cerquitelli, T.; Di Corso, E.; Proto, S.; Bethaz, P.; Mazzarelli, D.; Capozzoli, A.; Baralis, E.; Mellia, M.; Casagrande, S.; Tamburini, M. A Data-Driven Energy Platform: From Energy Performance Certificates to Human-Readable Knowledge through Dynamic High-Resolution Geospatial Maps. Electronics 2020, 9, 2132. https://doi.org/10.3390/electronics9122132
* Peck R Olsen C Devore JL. Introduction to Statistics and Data Analysis. 3rd ed. Australia: Thomson Brooks/Cole; 2008.
