[![published in: Bioinformatics](https://img.shields.io/badge/published%20in-Bioinformatics-ff69b4.svg?style=flat)](https://doi.org/10.1093/bioinformatics/btv205)

![chipPCR](https://github.com/michbur/chipPCR/blob/master/vignettes/logo.png)

The chipPCR package is a toolkit of functions to preprocess 
amplification curve data. Amplification data can be obtained from 
conventional PCR reactions or isothermal amplification reactions. The 
package contains functions to normalize and baseline amplification curves, 
a routine to detect the start of an amplification reaction, several 
smoothers for amplification data, a function to distinguish positive and 
negative amplification reactions and a function to determine the 
amplification efficiency. The smoothers are based on LOWESS, moving 
average, cubic splines, Savitzky-Golay and others.

In addition the first 
approximate approximate derivative maximum (FDM) and second approximate 
derivative maximum (SDM) can be calculated by a 5-point-stencil as 
quantification points from real-time amplification curves. chipPCR contains 
data sets of experimental nucleic acid amplification systems including the 
VideoScan HCU and a capillary convective PCR (ccPCR) system. The 
amplification data were generated by helicase dependent amplification (HDA) 
or polymerase chain reaction (PCR) under various temperature conditions. As 
detection system intercalating dyes (EvaGreen, SYBR Green) and hydrolysis 
probes (TaqMan) were used.

Installation
------------

chipPCR is available [on CRAN](http://cran.r-project.org/web/packages/chipPCR/), so installation is as simple as:

```
install.packages("chipPCR")
```

You can install the latest development version of the code directly from GitHub:

```
# Install devtools, if you haven't already.
source("https://install-github.me/michbur/chipPCR")
```
