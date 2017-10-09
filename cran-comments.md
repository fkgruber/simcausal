## Resubmission
simcausal 0.5.4
==============
This resubmission fixes one note. The other note is a FALSE POSITIVE.
Note from JSS editor: "The DOI in the CITATION is for a new JSS publication that will be registered after publication on CRAN."

## Test environments:
* local OS X install, R 3.3.1
* ubuntu 12.04 (on travis-ci), R 3.3.1
* win-builder

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* one NOTE: Found the following (possibly) invalid DOIs:
  DOI: 10.18637/jss.v081.i02
    From: inst/CITATION
    Status: Not Found
    Message: 404
    "The DOI in the CITATION is for a new JSS publication that will be registered after publication on CRAN."

## First submission of the new version
simcausal 0.5.4
==============
This update includes CITATION for the forcoming JSS simcausal publication. Note from JSS editor: "The DOI in the CITATION is for a new JSS publication that will be registered after publication on CRAN.""

## Test environments:
* local OS X install, R 3.3.1
* ubuntu 12.04 (on travis-ci), R 3.3.1
* win-builder

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* one NOTE: "The DOI in the CITATION is for a new JSS publication that will be registered after publication on CRAN."

## First submission of the new version
simcausal 0.5.3
==============
This version fixes a CRAN test error on R devel and a bug identified due to upcoming version of the data.table dependency. 
## Test environments:

## Test environments:
* local OS X install, R 3.3.1
* ubuntu 12.04 (on travis-ci), R 3.3.1
* win-builder

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* no NOTEs.

## Resubmission
simcausal 0.5.1
==============
This is a resubmission. This should fix the reverse dependency fail with the 'tmlenet' package.

## First submission of the new version
simcausal 0.5.1
==============
## Test environments:

## Test environments:
* local OS X install, R 3.2.4
* ubuntu 12.04 (on travis-ci), R 3.2.4
* win-builder (devel and release)

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* no NOTEs.

## Resubmission
simcausal 0.5.0
==============
This is a resubmission. In this version I have:

* Fixed the reverse dependency error for 'tmlenet' package

simcausal 0.5.0
==============
## Test environments:

## Test environments:
* local OS X install, R 3.2.3
* ubuntu 12.04 (on travis-ci), R 3.2.3
* win-builder (devel and release)

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* no NOTEs.

simcausal 0.4.0
==============

## Test environments:
* local OS X install, R 3.2.2
* ubuntu 12.04 (on travis-ci), R 3.2.2
* win-builder (devel and release)

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* no NOTEs.

* Adding importFrom("methods", "is") and adding methods to Imports field;
* Fixing a warning on v.0.3.0 for generic "melt" being exported twice by data.table and reshape2;

simcausal 0.3.0
==============

## Test environments:
* local OS X install, R 3.2.0
* ubuntu 12.04 (on travis-ci), R 3.2.2
* win-builder (devel and release)

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* no NOTEs.

* Please note that the R code in the vignette requires a substantial amount of time to run.

simcausal 0.2.0
==============

## Test environments:
* local OS X install, R 3.2.0
* ubuntu 12.04 (on travis-ci), R 3.2.0
* win-builder (devel and release)

## R CMD check --as-cran results:
* no ERRORs or WARNINGs.
* no NOTEs.

* Please note that the R code in the vignette requires a substantial amount of time to run.

simcausal 0.1
==============

## Resubmission 3:
This is a third resubmission. In this version I have:

* Removed \donttest{} sections from two examples in the help manual
* Removed last sentence of the "Description" that referred to the vignette
* Added skeleton NEWS and README.md files

## Resubmission 2:
This is a second resubmission. In this version I have:

* Reformatted all the R code in .Rd examples to be under 100 line width
* Made sure all the checks are passed when running R CMD check --as-cran

## Resubmission:
This is a resubmission. In this version I have:

* Converted the DESCRIPTION title to title case
* Removed . from the title end
* Removed VignetteBuilder line from the DESCRIPTION
* Removed 'simcausal.Rproj' file
* Reformatted all the R code in .Rd examples to be under 100 line width

## Initial submission to CRAN:

## Test environments:
* local OS X install, R 3.1.3
* win-builder (devel and release)

## R CMD check results
There were no ERRORs or WARNINGs. 



