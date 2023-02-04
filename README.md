# Temporal Attention Augmented Bilinear Network for Financial Time Series Data Analysis
In this repository you can find the implementation of the models proposed in [Temporal Attention Augmented Bilinear Network for Financial Time Series Data Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8476227&casa_token=ku1x8IhINb8AAAAA:FOCQwqaSbL8u5Cc9RbzessVNuFDyoTQE4IFToKVM4dI1LLW9w9TD80eaCev66PXQa1kU92q30w&tag=1). 

In particular I've implented B(TABL) and C(TABL) using pytorch.

In the notebook is proposed all the machine learning pipeline, starting from the loading of the dataset, passing from the labeling method, creation of the datasets and dataloaders, ending with the train, validation and test.

I reached the same results of the original paper.

# Usage

To run the code you just have to download the [FI-2010 dataset](https://etsin.fairdata.fi/dataset/73eb48d7-4dbc-4a10-a52a-da745b47a649/data) and change the data path, then the notebook will do the rest, including the training and testing.

