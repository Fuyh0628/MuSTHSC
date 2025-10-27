# Multi-Modal Integration of Multi-Slice Spatial Transcriptomics, Histology, and scRNA-seq for Cross-Slice Spatial Domain Identification

![MuSTHSC](https://github.com/Fuyh0628/STMGAMF/blob/master/Model.jpg)

## Requirements

You'll need to install the following packages in order to run the codes.

* scanpy==1.11.1
* anndata==0.11.4
* numpy==1.24.0
* pandas==2.2.3
* squidpy==1.6.5
* scipy==1.11.4
* gudhi==3.11.0
* networkx==3.2.1
* matplotlib==3.8.2
* louvain==0.8.2
* rpy2==3.5.17
* seaborn==0.13.2
* hnswlib==0.8.0
* annoy==1.17.3
* tqdm==4.64.1
* torch==2.1.2+cu121
* torch-geometric==2.6.1
* pyproj==3.7.1
* future==1.0.0

## Usage

### Model Training and Testing

Run ***run_MuSTHSC_on_DLPFC_data.ipynb*** to train and test the MuSTHSC model

### Results
 
The results, including predictions and evaluation metrics, are saved in the folder ***Results***.


