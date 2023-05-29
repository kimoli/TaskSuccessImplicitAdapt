# Code and data repository for *Exploring the role of task success in implicit motor adaptation*
## N Al-Fawakhiri, A Ma, JA Taylor, OA Kim

### How are things organized in this repository?
All filenames include the figure number for which the data/analysis/output is relevant.
Files with names beginning with...:
+ "analysis_" contain the R scripts used to analyze the data. There are lines flagged with "TODO"s that you will need to modify so that they point to the data in the path where you have downloaded the repository on your computer.
+ "data_" contain the trial-wise data used in the analyses
+ "output_" contain the output from the R scripts in the repository. They are labelled with the figure and panel that the data correspond to.


### R package dependencies
+ cowplot
+ dplyr
+ effsize
+ ggplot2
+ ggpubr
+ plyr
+ psych
+ readxl
+ rstatix

### R package citations
+ Claus O. Wilke (2020). cowplot: Streamlined Plot Theme and Plot Annotations for 'ggplot2'. R package version 1.1.1.  https://CRAN.R-project.org/package=cowplot
+ Hadley Wickham, Romain François, Lionel Henry and Kirill Müller (2021). dplyr: A Grammar of Data Manipulation. R package version 1.0.5.  https://CRAN.R-project.org/package=dplyr
+ Torchiano M (2020). _effsize: Efficient Effect Size Computation_. doi: 10.5281/zenodo.1480624 (URL: https://doi.org/10.5281/zenodo.1480624), R package version 0.8.1, <URL: https://CRAN.R-project.org/package=effsize>.
+ H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016.
+ Alboukadel Kassambara (2020). ggpubr: 'ggplot2' Based Publication Ready Plots. R package version 0.4.0. https://CRAN.R-project.org/package=ggpubr
+ Hadley Wickham (2011). The Split-Apply-Combine Strategy for Data Analysis. Journal of Statistical Software, 40(1), 1-29. URL http://www.jstatsoft.org/v40/i01/.
+ Revelle, W. (2020) psych: Procedures for Personality and Psychological Research, Northwestern University, Evanston, Illinois, USA, https://CRAN.R-project.org/package=psych Version = 2.1.3,.
+ Hadley Wickham and Jennifer Bryan (2019). readxl: Read Excel Files. R package version 1.3.1. https://CRAN.R-project.org/package=readxl
+ Alboukadel Kassambara (2021). rstatix: Pipe-Friendly Framework for Basic Statistical Tests. R package version 0.7.0. https://CRAN.R-project.org/package=rstatix