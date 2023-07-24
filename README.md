# ColumnarFormatsEval
This repository provides the necessary information and links to reproduce the experiments and results presented in the paper "A Deep Dive into Common Open Formats for Analytical DBMSs". 

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
