# ColumnarFormatsEval
This repository provides the necessary information and links to reproduce the experiments and results presented in the paper "[A Deep Dive into Common Open Formats for Analytical DBMSs](https://people.csail.mit.edu/chunwei/pub/p3044-liu.pdf)". 
```
@article{10.14778/3611479.3611507,
author = {Liu, Chunwei and Pavlenko, Anna and Interlandi, Matteo and Haynes, Brandon},
title = {A Deep Dive into Common Open Formats for Analytical DBMSs},
year = {2023},
issue_date = {July 2023},
publisher = {VLDB Endowment},
volume = {16},
number = {11},
issn = {2150-8097},
url = {https://doi.org/10.14778/3611479.3611507},
doi = {10.14778/3611479.3611507},
abstract = {This paper evaluates the suitability of Apache Arrow, Parquet, and ORC as formats for subsumption in an analytical DBMS. We systematically identify and explore the high-level features that are important to support efficient querying in modern OLAP DBMSs and evaluate the ability of each format to support these features. We find that each format has trade-offs that make it more or less suitable for use as a format in a DBMS and identify opportunities to more holistically co-design a unified in-memory and on-disk data representation. Our hope is that this study can be used as a guide for system developers designing and using these formats, as well as provide the community with directions to pursue for improving these common open formats.},
journal = {Proc. VLDB Endow.},
month = {aug},
pages = {3044–3056},
numpages = {13}
}
```

## Datasets

The experiments in the paper are based on the following datasets:

1. [Public BI benchmark](https://github.com/cwida/public_bi_benchmark)
2. [Join Order benchmark (JOB)](https://github.com/gregrahn/join-order-benchmark)
3. [CodecDB](https://github.com/Tranway1/DatasetEncoder)

## Code Repositories

The code for the experiments is divided into several repositories, each focusing on a specific aspect of the evaluation:

1. [Real-world dataset compression evaluations](https://github.com/Tranway1/DatasetEncoder): This repository contains the code for evaluating the compression performance of the different formats on real-world datasets.

2. [Parquet and Arrow experiments](https://github.com/Tranway1/Arrow): This repository contains the code for the experiments that evaluate the performance of Parquet and Arrow.

3. [ORC experiments](https://github.com/Tranway1/ORC): This repository contains the code for the experiments that evaluate the performance of ORC.

4. [In memory Parquet](https://github.com/Tranway1/IMP): This repository contains the code for the experiments that evaluate the performance of in-memory Parquet.

## Instructions

To reproduce the results, follow the instructions provided in the readme file of each repository. Please note that you will need to download the datasets and place them in the appropriate directories as specified in the instructions.

## Contact

If you encounter any issues or have any questions about reproducing the results, please open an issue in the relevant repository. We will do our best to assist you.
