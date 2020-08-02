# Neural Pooling for Graph Neural Networks

This is the code for my IAS SRFP 2020 Report "Neural Pooling for Graph Neural Networks".

## System requirement

#### Programming language
```
Python 3.6
```
#### Python Packages
```
PyTorch > 1.0.0, tqdm, networkx, numpy
```

## Setup

If you want to try our proposed Neural Pooling methods, copy the **graphcnn.py** file into the **models** folder from either the **neural_pooling_1** folder or the **neural_pooling_2** folder.
The **graphcnn.py** file currently in the **model** folder contains code for SUM/AVG Pooling.

## Run the code

We provide scripts to run the experiments. For bioinformatics datasets, run
```
chmod +x run_bio.sh
./run_bio.sh [DATASET] [GPU_ID] [BATCH_SIZE] [HIDDEN_DIM]
```

For the social network datasets, run
```
chmod +x run_social.sh
./run_social.sh [DATASET] [GPU_ID] [BATCH_SIZE] [HIDDEN_DIM]
```
