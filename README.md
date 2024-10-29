# README - Homework 1

## Report Abstract
This report observes a dataset held by the University of California in Irvine related to students enrolled in various undergraduate programs and containing information from the time of their enrollment, academic performance from the first two semesters, and more. The paper aims to calculate the effect of whether student attendance in the daytime or evening has an effect on whether they remain in school or dropout. Included in the discussion are methods of how to control for any confounding variables, limitations of the analysis, etc. 

## Personal Info

-   Natalie Huante
-   Student ID: 2374481
-   Email: huante\@chapman.edu
-   Course: CPSC 540-01 - Statistical Machine Learning I
-   Term: Fall 2024 Semester
-   Assignment 1

## Files Included

-   README.qmd file
-   Homework1.qmd
    -   Includes the R Code used to produce any figures, tables, etc. for the report.
-   Report PDF File
    -   Includes the in-detail description, proposal, and discussion on the analysis.
-   Other files produced by R Studio

## Known Compile or Runtime Errors

-   There are no compile and/or runtime errors that I am aware of in the .qmd file included.
-   There are a couple lines of code that were used to transform some part of the dataset and are now commented out. This is because they only needed to be run once, otherwise, they can cause an error. For example, on line 416 of the .qmd file, the code is commented out. It's purpose was to transform the target column from 3 categories into 2 so that we can use a binomial family later on. Therefore, if that line is ran again, R will error out since it will look for a column with values as strings, but is now made of integers. This shouldn't cause any issues moving forwards, but I thought was worth mentioning.

## References

-   These can also be found under the references section of the report or at the bottom of the .qmd file.

-   ggdag manual

    -   https://cran.r-project.org/web/packages/ggdag/vignettes/intro-to-ggdag.html

-   different layouts for ggdag(layout = "")

    -   https://thomasp85.r-universe.dev/ggraph/doc/manual.html#ggraph

-   presentation on causal diagrams in R

    -   https://user2020.lucymcgowan.com/02-dags.html#40
    -   https://ggdagcand3.netlify.app/?panelset1=using-dagitty.net2#38

-   R colors To Use

    -   https://r-charts.com/colors/

-   Coefficient Interpretation

    -   https://towardsdatascience.com/a-simple-interpretation-of-logistic-regression-coefficients-e3a40a62e8cf
    -   https://stats.oarc.ucla.edu/other/mult-pkg/faq/general/faq-how-do-i-interpret-odds-ratios-in-logistic-regression/

-   Reddit On GLM Weights Argument

    -   https://www.reddit.com/r/rstats/comments/6zg2f2/struggling_with_including_weights_in_a_binomial/

-   Binomial Vs Quasibinomial Distributions

    -   https://stats.stackexchange.com/questions/91724/what-is-quasi-binomial-distribution-in-the-context-of-glm
    -   https://randomeffect.net/post/2020/10/12/quasi-binomial-in-r-glm/
    -   https://stat.ethz.ch/R-manual/R-devel/library/stats/html/family.html

-   Dr. P's Lecture Slides

    -   https://github.com/chelseaparlett/CPSC540ParlettPelleriti/tree/main/LectureSlides
- Data Set
    - Realinho, Valentim, et al. "Predict Students' Dropout and Academic Success." UCI Machine Learning Repository, 2021, https://doi.org/10.24432/C5MC89. 
