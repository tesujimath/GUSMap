# GUSMap

[![gplv3+](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.html)

Genotyping Uncertainty with Sequencing data and linkage MAPping (GUSMap).

An R package for performing linkage mapping using low and/or high coverage sequencing data without requiring filtering with respect to read depth.

### Installation:

The easiest way to install GUSMap in R is using the devtools package.

```
install.packages("devtools")
devtools::install_github("tpbilton/GUSbase")
devtools::install_github("tpbilton/GUSMap")
```

Note: Some of the functions are coded in C and therefore an appropriate C compiler is needed for the package to work. For windows OS, Rtools (https://cran.r-project.org/bin/windows/Rtools/) provides a compiler. 

### Tutorials:

There are three different types of mapping populations that are available GUSMap can handle. There is a tutorial for each of these mapping populations explaining how to use GUSMap to construct linkage maps.

* A back-cross (BC) population. See the [BC Introduction](http://htmlpreview.github.io/?https://github.com/tpbilton/GUSMap/blob/master/inst/doc/Introduction_BC.html) tutorial.
* A full-sib family. See the [FS Introduction](http://htmlpreview.github.io/?https://github.com/tpbilton/GUSMap/blob/master/inst/doc/Introduction_FS.html) tutorial.
* An intercross/F2 (IC) population. See the [IC Introduction](http://htmlpreview.github.io/?https://github.com/tpbilton/GUSMap/blob/master/inst/doc/Introduction_IC.html) tutorial.

### Development:

This package is under contiuned developement. If you have any suggests for improvement or additional features you like to see, I'd suggest posting a question under the Issues. I'm also happy for people to suggest changes via a pull request provided it fits within the favour of the package.

### Citation:

To cite this R package:

Bilton, T.P., Schofield, M.R., Black, M.A., Chagn&#233;, D., Wilcox, P.L., & Dodds, K.G. (2018). Accounting for errors in low coverage high-throughput sequencing data when constructing genetic maps using biparental outcrossed populations. *Genetics*, *209*(1), 65--76. doi:[10.1534/genetics.117.300627](http://www.genetics.org/content/209/1/65) 

### Funding:
The initial development of this package was partially funded by the Ministry of Business, Innovation and Employment via its funding of the “Genomics for Production & Security in a Biological Economy” programme (Contract ID C10X1306).
