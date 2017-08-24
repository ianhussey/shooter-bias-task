# The Shooter Bias Task

## Author

Ian Hussey (ian.hussey@ugent.be)

## License

GPLv3+

## Overview

The Shooter Bias Task, sometimes called the Police Officer's Dilemma (Correll et al., 2002), assesses racial biases in the decision to "shoot" at images of armed/unarmed men. Millisecond provide a working implementation of it in Inquisit, but I found their caculation of signal detection analysis metrics (sensitivity/d' and response bias/c) to be somewhat opaque. 

Essien, Stelter, et al. (2017) modified the original Millisecond script and provided an R script to process d' and c that I found more accessible. I refactored Essien et al's code from a ddply implementation to tidyverse, which I provide here. 

## References

Correll, J., Park, B., Judd, C. M., & Wittenbrink, B. (2002). The police officer's dilemma: Using ethnicity to disambiguate potentially threatening individuals. Journal of Personality and Social Psychology, 83, 1314-1329.

## Original code

Inquisit script:

http://www.millisecond.com/download/library/podt/

Modified inquisit script and processing/analysis R code:

https://osf.io/rq6h2/