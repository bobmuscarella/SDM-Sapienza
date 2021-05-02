Introduction to SDMs: theory and practice in R
================
Bob Muscarella
Sapienza University, Rome (June 9-11, 2021)

### **Introduction**

**Learning objectives**: By the end of this course, you will be able to:

-   Know the basic theory and concepts behind SDMs / ENMs
-   Design, build and evaluate SDMs / ENMs using automated R scripts
-   Understand the strengths and limitations of SDMs / ENMs for
    different purposes
-   Use SDMs / ENMs to describe, predict, and project species
    distributions in space and time

### **Day 0**: Before the course

**Reading**: Please read these papers before the course begins as they
provide important background information. We will discuss them on Day 1.

-   [Merow et al. (2014) What do we gain from simplicity versus
    complexity in species distribution models? Ecography, 37,
    1267–1281.]()

-   [Elith, J., & Graham, C. H. (2009) Do they? How do they? WHY do they
    differ? On finding reasons for differing performances of species
    distribution models. Ecography 32(1), 66-77.]()

-   [Elith, J., & Leathwick, J. R. (2009). Species distribution models:
    ecological explanation and prediction across space and time. Annual
    Review of Ecology, Evolution, and Systematics 40, 677-697.]()

**R Exercise**: Please download and complete these following R exercise.

-   R Exercise 1: Getting Started

### **Day 1**: Introduction: data acquisition and cleaning

**Morning session** (*Theory*)

-   Overview and personal introductions
-   **Lecture 1:** The what, how, why of SDMs/ENMs
-   **Lecture 2:** Data-to-model: Walk-through an example analysis

**Afternoon session** (*Practical*)

-   Obtaining and cleaning data
    -   Occurrence records
        -   [rgbif](https://docs.ropensci.org/rgbif/index.html)
        -   [CoordinateCleaner](https://ropensci.github.io/CoordinateCleaner/)
    -   Climate variables
        -   Manual downloads ([Chela](https://chelsa-climate.org/);
            [WorldClim](https://www.worldclim.org/))
        -   [raster](https://cran.r-project.org/web/packages/raster/raster.pdf)
        -   [climatedata](https://github.com/MirzaCengic/climatedata)
        -   [chelsaDL](https://github.com/matthewkling/chelsaDL)
        -   [climateR](https://github.com/mikejohnson51/climateR)
    -   Other
        -   Elevation
        -   Land-use
        -   Soil: HWSD
        -   …

### **Day 2**: Models: algorithms and evaluations

**Morning session** (*Theory*)

-   **Lecture 3:** Variety of modeling algorithms
    -   Presence-absence
    -   Presence-only
    -   “Next generation”
        -   Joint SDMs
        -   [hSDM](https://ecology.ghislainv.fr/hSDM/)
        -   HMSC (*hierarchical modeling of species and communities*)
            -   [HMSC
                Homepage](https://www2.helsinki.fi/en/researchgroups/statistical-ecology/hmsc)
            -   [MEE
                publication](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13345)
            -   [Github page](https://github.com/hmsc-r/HMSC)

**Afternoon session** (*Practical*)

-   Overview of algorithms
    -   Maxent
    -   Embarcadero
    -   HSDM

### **Day 3**: Applications: possibilities and precautions

**Morning session** (*Theory*)

Topics - Model evaluation - Projection

**Afternoon session** (*Practical*)

### **Additional Resources**

This course is a very brief introduction to the broad topic of SDMs /
ENMs. There are lots of other excellent resources available online. Here
are some suggestions:

-   ENM2020 course (organized by Townsend Peterson)
    -   [Schedule with downloadable slide
        PDFs](https://docs.google.com/spreadsheets/d/1RQu1XRKyYfrnFI2V1g677d0sf8tFxC2xUvb96cbP02s/edit?usp=sharing)
    -   [YouTube playlist of
        lectures](https://youtube.com/playlist?list=PLhEJuWmv8Jf67qSdifDvgOk5DOJsNNiam)
-   [Intro to SDMs course by Damaris
    Zurell](https://damariszurell.github.io/SDM-Intro/)
-   [Intro to SDMs course by Cory
    Merow](https://cmerow.github.io/RDataScience/101SDMs.html)
-   [Intro to SDMs course by Adam
    Smith](http://www.earthskysea.org/best-practices-in-species-distribution-modeling-a-workshop-in-r/)

### **Reading**

-   Merow, C., Smith, M.J., Edwards, T.C., Jr, Guisan, A., McMahon,
    S.M., Normand, S., et al. (2014). What do we gain from simplicity
    versus complexity in species distribution models? Ecography , 37,
    1267–1281.

-   Merow, C., Smith, M. & Silander, J.A. (2013). A practical guide to
    Maxent: what it does, and why inputs and settings matter. Ecography
    , 36, 1–12.

-   Muscarella, R., Galante, P.J., Soley-Guardia, M., Boria, R.A., Kass,
    J.M., Uriarte, M., et al. (2014). ENMeval: An R package for
    conducting spatially independent evaluations and estimating optimal
    model complexity for Maxent ecological niche models. Methods Ecol.
    Evol., 5, 1198–1205.

-   [Zurell, D., Franklin, J., König, C., Bouchet, P.J., Dormann, C.F.,
    Elith, J., et al. (2020). A standard protocol for reporting species
    distribution models. Ecography, 43,
    1261–1277.](https://github.com/bobmuscarella/Sapienza-SDM-course/blob/25d9eb50324a9f66c596b7af0b5da10553fa2c06/Literature/Zurell%20et%20al.%202020%20Ecography.pdf)

-   Araújo, M. B., R. P. Anderson, A. M. Barbosa, C. M. Beale, C. F.
    Dormann, R. Early, R. A. Garcia, et al. 2019. “Standards for
    Distribution Models in Biodiversity Assessments.” Science Advances
    5: eaat4858.
