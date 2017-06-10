******Quantum-inspired Evolutionary Algorithms for Community Detection in Social Networks***

****Folder  information****

**reports**
Contains the results

**data**
Contains the data used by the code

**code**
A complete directory containing the code files, data files, and script files.



****Code information****

We have proposed two algorithms:
1. Binary chromosome QIEA
2. Numeric chromosome QIEA

Code folder contains the serial and the parallel (CUDA-based) versions of these algorithms.

qieaBinChromosome.c: Serial Binary chromosome QIEA
qieaNumChromosome.c: Serial Numeric chromosome QIEA
qieaBinChromosome.cu: Parallel Binary chromosome QIEA
qieaNumChromosome.cu: Parallel Numeric chromosome QIEA


***Shell script files***

Provided as examples to understand the running of the code.


***Environement used to run the code***

The proposed algorithms were run on Dell Precision T7610 having Intel Xeon CPU E5-2620 v2 $@$ 2.10 GHz X17 and NVIDIA Tesla K40 graphics processing unit (GPU) running ubuntu 12.04 LTS, 32 GB RAM, and 1.5 TB HDD. 


***Please cite***
Gupta, Shikha, Sheetal Taneja, and Naveen Kumar. "Quantum inspired genetic algorithm for community structure detection in social networks." Proceedings of the 2014 Annual Conference on Genetic and Evolutionary Computation. ACM, 2014.

Gupta, Shikha, and Naveen Kumar. "Parameter tuning in quantum-inspired evolutionary algorithms for partitioning complex networks." Proceedings of the Companion Publication of the 2014 Annual Conference on Genetic and Evolutionary Computation. ACM, 2014.