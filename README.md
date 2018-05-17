tmap: thematic maps in R
===

[![Build Status](https://travis-ci.org/mtennekes/tmap.png?branch=master)](https://travis-ci.org/mtennekes/tmap)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/mtennekes/tmap?branch=master&svg=true)](https://ci.appveyor.com/project/mtennekes/tmap)
[![Coverage Status](https://img.shields.io/codecov/c/github/mtennekes/tmap/master.svg)](https://codecov.io/github/mtennekes/tmap?branch=master)
[![License](https://img.shields.io/badge/License-GPL%20v3-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/gpl-3.0.html) 
[![CRAN](http://www.r-pkg.org/badges/version/tmap)](https://cran.r-project.org/package=tmap) 
[![Downloads](http://cranlogs.r-pkg.org/badges/tmap?color=brightgreen)](http://www.r-pkg.org/pkg/tmap)

[`tmap`][1] is an actively maintained open-source [R][2]-library for drawing thematic maps, written by [Martijn Tennekes][3]. The API is based on [*A Layered Grammar of Graphics*][4] by Hadley Wickham and resembles the syntax of `ggplot2`, a popular R-library for drawing charts.

<span>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/ClassicMap"><img src="http://www.von-tijn.nl/tijn/research/tmap/icons/classic.jpg" alt="Classic World Map" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/BubbleMap"><img src="http://www.von-tijn.nl/tijn/research/tmap/icons/bubble.jpg" alt="Bubble Map" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/BubbleMap"><img src="http://www.von-tijn.nl/tijn/research/tmap/icons/view_metro2.jpg" alt="Bubble Map" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/WorldFacets"><img src="http://www.von-tijn.nl/tijn/research/tmap/icons/world_facets2.jpg" alt="World facets" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/USChoropleth"><img src="http://www.von-tijn.nl/tijn/research/tmap/icons/USchoro.jpg" alt="US Choropleth" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/USChoropleth"><img src="http://www.von-tijn.nl/tijn/research/tmap/icons/US_PR.jpg" alt="US Choropleth" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/LondonCrimes">
<img src="http://www.von-tijn.nl/tijn/research/tmap/icons/crimes3.jpg" alt="London Crimes" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/LondonCrimes">
<img src="http://www.von-tijn.nl/tijn/research/tmap/icons/crimes4.jpg" alt="London Crimes" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/LondonCrimes">
<img src="http://www.von-tijn.nl/tijn/research/tmap/icons/crimes5.jpg" alt="London Crimes" height="125px"/></a>
<a href = "https://github.com/mtennekes/tmap/tree/master/demo/LondonCrimes">
<img src="http://www.von-tijn.nl/tijn/research/tmap/icons/view_crimes2.jpg" alt="London Crimes" height="125px"/></a>
</span>


Installation
------------

`tmap` is available on [CRAN](http://cran.r-project.org/package=tmap) (the latest version is 1.11-2, published on 2018-04-10). Version 2.0 will be published soon (see below). Installation is straightforward:

```r
install.packages("tmap")
```

However, for some operating systems require additional libraries. The installation procedure is as follows:

**Windows**
No additional installation required.

**Linux (Ubuntu)**
See installation script for [Ubuntu 16](https://github.com/mtennekes/tmap/blob/master/ubuntu_16_installation.sh) and [17](https://github.com/mtennekes/tmap/blob/master/ubuntu_17_installation.sh). See also [issue thread](https://github.com/mtennekes/tmap/issues/150).

**macOS**
See http://www.kyngchaos.com and [issue thread](https://github.com/mtennekes/tmap/issues/149).


Development
------------


The latest development version can be installed using `devtools`. In order to use the development version of `tmap`, it is recommended to use the development version of `tmaptools` as well (see [tmaptools](http://github.com/mtennekes/tmaptools)):

```r
library(devtools)
install_github("mtennekes/tmaptools")
install_github("mtennekes/tmap")
```

See [NEWS](https://github.com/mtennekes/tmap/blob/master/pkg/NEWS) for the latest features and improvements and the [issue list](https://github.com/mtennekes/tmap/issues) for discussions of enhancements and bugs.

Do you want to help with the development of the package? Please let me know! Any feedback, requests, tips, or bug reports are welcome!


Usage
-----

```r
library(tmap)
```

Reference
----
[Tennekes, M., 2018, tmap: Thematic Maps in R, Journal of Statistical Software, 84(6), 1-39](https://doi.org/10.18637/jss.v084.i06)


Vignettes 
-----

*Version 1.x*

[tmap in a nutshell][6] 

[tmap modes: plot and interactive view][11]

*Version 2.x*

[tmap: get started!](https://github.com/mtennekes/tmap/blob/master/vignettes/tmap-getstarted.Rmd)

[tmap modes: plot and interactive view](https://github.com/mtennekes/tmap/blob/master/vignettes/tmap-modes.Rmd)

[tmap: what is changed in version 2.0?](https://github.com/mtennekes/tmap/blob/master/vignettes/tmap-changes-v2.Rmd)

Examples and tutorials
-----

[Example 1: Metropolitan Areas](https://github.com/mtennekes/tmap/tree/master/demo/BubbleMap)

[Example 2: Classic World Map](https://github.com/mtennekes/tmap/tree/master/demo/ClassicMap)

[Example 3: Two World Views](https://github.com/mtennekes/tmap/tree/master/demo/WorldFacets)

[Example 4: Obesity in the United States](https://github.com/mtennekes/tmap/tree/master/demo/USChoropleth)

[Example 5: Crimes in Greater London](https://github.com/mtennekes/tmap/tree/master/demo/LondonCrimes)

[Demo: tmap in RMarkdown](https://github.com/mtennekes/tmap/blob/master/demo/tutorials/rmarkdown_tmap.R)

[Demo: tmap in Shiny](https://github.com/mtennekes/tmap/blob/master/demo/tutorials/shiny_tmap.R)


Presentations
-----

* [Plotting spatial data with R] (eRum 2018) https://github.com/mtennekes/tmap-workshop
* Exploring and presenting maps with tmap (useR!2017) [(Abstract)][20] [(Presentation)][21]
* [tmap: creating thematic maps in a flexible way (useR!2015)][10]


Other resources
-----

* [Geocomputation with R; Making maps with R, Robin Lovelace, Jakub Nowosad, Jannes Muenchow][23]
* [Working with Spatial Data and using tmap, Samantha A. Alger][22]
* [Computer World: Mapping in R just got a whole lot easier][18]
* [National Socio-Environmental Synthesis Center: Maps in R][19]
* [Introduction to visualising spatial data in R][9]
* [Blog post StatialControl][7]
* [Blog post TWIAV][8]
* [Computer World: Create maps in R in 10 (fairly) easy steps][12]
* [Computer World: Great R packages for data import, wrangling and visualization][17]
* [Tutorial Visualising spatial data: from base to shiny - workshop][15]
* [Stack Overflow questions (#tmap)][16]


Getting help
-----

There are two main places to get help with `tmap`:

1.  [stackoverflow](http://stackoverflow.com/tags/tmap) is a great source of answers to common tmap questions. It is also a great place to get help, once you have created a reproducible example that illustrates your problem. Please tag your questions with *tmap*.
2.  If you have a request or if think your problem is caused by a bug, please open an [issue](https://github.com/mtennekes/tmap/issues), preferably with are reproducible example.


  [1]: http://cran.r-project.org/web/packages/tmap/index.html
  [2]: http://stackoverflow.com/tags/r/info
  [3]: http://stackoverflow.com/users/1393348/martijn-tennekes
  [4]: http://vita.had.co.nz/papers/layered-grammar.pdf
  [5]: https://github.com/mtennekes/tmap
  [6]: https://cran.r-project.org/web/packages/tmap/vignettes/tmap-nutshell.html
  [7]: http://spatcontrol.net/SpatialControl/2015/11/06/tmap-r-package/
  [8]: http://www.twiav.nl/en/blog0002en.php
  [9]: https://cran.r-project.org/doc/contrib/intro-spatial-rl.pdf
  [10]: http://von-tijn.nl/tijn/research/presentations/tmap_user2015.pdf
  [11]: https://cran.r-project.org/web/packages/tmap/vignettes/tmap-modes.html
  [12]: http://cwrld.us/Rmaps10
  [13]: https://github.com/mtennekes/tmap/blob/master/demo/US_choropleth.R
  [14]: https://github.com/mtennekes/tmap/blob/master/demo/crimes_in_Greater_London.R
  [15]: https://github.com/Robinlovelace/Creating-maps-in-R/blob/master/vignettes/vspd-base-shiny.Rmd
  [16]: http://stackoverflow.com/questions/tagged/tmap
  [17]: http://www.computerworld.com/article/2921176/business-intelligence/great-r-packages-for-data-import-wrangling-visualization.html
  [18]:	http://www.computerworld.com/article/3175623/data-analytics/mapping-in-r-just-got-a-whole-lot-easier.html
  [19]: https://sesync-ci.github.io/maps-in-R-lesson/
  [20]: http://von-tijn.nl/tijn/research/publications/abstract_tmap.pdf
  [21]: http://von-tijn.nl/tijn/research/presentations/tmap_user2017.pdf
  [22]: https://gotellilab.github.io/Bio381/StudentPresentations/SpatialDataTutorial.html
  [23]: http://geocompr.robinlovelace.net/adv-map.html
  