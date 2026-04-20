# Workshops for the `BayesSSD` R package

This is the repository for workshops around the R package `BayesSSD`, which performs simulation-based sample size determination for Bayesian hypothesis testing within the multilevel framework.

## Getting Started

### Installing

To install the latest release version of `BayesSSD` from GitHub, follow these steps:

```
install.packages("devtools")                                         # install devtools package
devtools::install_github("ulrichlosener/BayesSSD", upgrade="never")  # install BayesSSD from GitHub
library(BayesSSD)                                                    # load BayesSSD package
```

### Executing sample size determination algorithm (example)

```
# for informative hypotheses in cluster randomized trials
SSD_crt_inform()```

# for longitudinal trials

SSD_longit()
```

## Authors
The authors of this package and workshops are Camila Barragan-Ibanez and Ulrich Lösener, both affiliated to Utrecht University. Their supervisor is Mirjam Moerbeek.
