---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

I have developed or co-developed a number of software packages for ecology in the statistical programming language R. I work both privately and collaboratively on Github (username [ndimhypervol](https://github.com/jamiemkass)), so please convey any comments on software as Github issues and I'll be sure to respond.

Lead developer:

- The [**Wallace** ecological modeling application](https://wallaceecomod.github.io/) (R package [`wallace`](https://CRAN.R-project.org/package=wallace)) features an interactive graphical user interface and walks users through a complete species distribution modeling analysis, including data collection, data processing, study extent selection, model complexity tuning, and model predictions

- **ENMeval** 2.0.0, a complete redesign of the original package (see below) is in current development with many new features.

Co-developer:

- **ENMeval** 0.3.1 (R package [`ENMeval`](https://CRAN.R-project.org/package=ENMeval)) is the first software in R to provide automated model complexity tuning for species distribution models (here, Maxent) and tools to partition data for cross validation in a variety of ways, including spatial options.

- **Range Model Metadata Standards** (R package [`rangeModelMetadata`](https://CRAN.R-project.org/package=rangeModelMetadata)), or RMMS, offers a hierarchical metadata framework for species distribution models and tools to autogenerate metadata objects from data and models in R.

- **occCite** (R package [`occCite`](https://CRAN.R-project.org/package=occCite)) is a collection of tools for  downloading and taxonomically verifying species occurrence data, gathering metadata on both database aggregators and primary providers, and generating citations on this metadata for publications.

- **maskRangeR** (R package [`maskRangeR`](https://cmerow.github.io/maskRangeR/)) is a collection of tools for processing potential range predictions made with species distribution models to estimate species' current ranges, and includes both expert-driven and data-driven methods 

*References*

**Kass, J. M.**, Vilela, B., Aiello‐Lammens, M. E., Muscarella, R., Merow, C., & Anderson, R. P. (2018). Wallace: A flexible platform for reproducible modeling of species niches and distributions built for community expansion. *Methods in Ecology and Evolution*, 9(4), 1151-1156. [https://doi.org/10.1111/2041-210X.12945](https://doi.org/10.1111/2041-210X.12945)

Muscarella, R., Galante, P. J., Soley‐Guardia, M., Boria, R. A., **Kass, J. M.**, Uriarte, M., & Anderson, R. P. (2014). ENM eval: An R package for conducting spatially independent evaluations and estimating optimal model complexity for Maxent ecological niche models. *Methods in Ecology and Evolution*, 5(11), 1198-1205. [https://doi.org/10.1111/2041-210X.12261](https://doi.org/10.1111/2041-210X.12261)

Merow, C., Maitner, B. S., Owens, H. L., **Kass, J. M.**, Enquist, B. J., Jetz, W., & Guralnick, R. (2019). Species' range model metadata standards: RMMS. *Global Ecology and Biogeography*, 28(12), 1912-1924. [https://doi.org/10.1111/geb.12993](https://doi.org/10.1111/geb.12993)

Owens, H. L., Merow, C., Maitner, B., *Kass, J. M.*, Barve, V., & Guralnick, R. P. (2020). occCite: Tools for Querying and Managing Large Biodiversity Occurrence Datasets. R package version 0.2.0. [https://github.com/hannahlowens/occCite](https://github.com/hannahlowens/occCite)

Merow, C., Galante, P. J., Babich Morrow, C., **Kass, J. M.**, Moore, A., Grisales-Betancur, V., Gerstner, B., Velasquez, J., Anderson, R. P., & Blair, M. E. (2020). maskRangeR: Improving spatial and temporal accuracy of species distribution models. R package version 1.0. [https://github.com/cmerow/maskRangeR](https://github.com/cmerow/maskRangeR)
