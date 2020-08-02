# Neural Pooling for Graph Neural Networks

This is the code for my IAS SRFP 2020 Report "Neural Pooling for Graph Neural Networks".

The ``Neural-Pooling`` folder contains code.
The ``Papers`` folder contains some papers referred.
The ``Presentations`` folder contains Keynote presentations of each week.

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

If you want to try our proposed Neural Pooling methods, copy the **graphcnn.py** file into the ``Neural-Pooling/models`` folder from either the ``Neural-Pooling/neural_pooling_1`` folder or the ``Neural-Pooling/neural_pooling_1`` folder.

The **graphcnn.py** file currently in the ``Neural-Pooling/models`` folder contains code for SUM/AVG pooling.

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
