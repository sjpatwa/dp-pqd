﻿# DP-PQD: Privately Detecting Per-Query Gaps In Synthetic Data Generated By Black-Box Mechanisms

## Framework

### Data

We consider the following dataset for the private database $D$:
 - [IPUMS-CPS Dataset](https://cps.ipums.org/cps/) - used to create the 2011_2019_D.csv file. See [paper](https://arxiv.org/abs/2309.08574) for details.

### File structure
 - COUNT.ipynb - Implementation for $LM_{count}$ and $EM_{count}$, followed by the queries and code used for the $COUNT$ query experiments. 
 - MEDIAN.ipynb - Implementation for $EM_{med}$ and $Hist_{med}$, followed by the queries and code used for the $MEDIAN$ query experiments. 
 - SUM_*.ipynb - Files divided based on the solution and also the parameter being varied. Implementation for $LM_{sum}, R2T_{sum}$, and $SVT_{sum}$, followed by the queries and code used for the $SUM$ query experiments.

### Environment
We have implemented the per-query deciders in Python $3.8.8$ using Pandas and NumPy libraries. All experiments were run on Apple M$1$ CPU @$3.2$ GHz with $16$ GB of RAM.
