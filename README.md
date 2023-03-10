# Empirical_Study_on_Code_Summarization
There are 4 datasets and 4 models we use in the paper: 

**Does Code Summarization Model Load Too Much? Function Signature May Be All That Need**

## Datasets

Four open-source dataset including:
### TLC

Source paper: [Summarizing Source Code with Transferred API Knowledge](https://doi.org/10.24963/ijcai.2018/314)

The dataset is available in GitHub: [TL-CodeSum/data](https://github.com/xing-hu/TL-CodeSum/tree/master/data)

We use this dataset directly, as there are no duplicates.

### Funcom
Source paper: [A neural model for generating natural language summaries of program subroutines](https://doi.org/10.1109/ICSE.2019.00087)

The source dataset is available in website: [FCM](https://figshare.com/s/fe32740133b33d719ab5)

We select one tenth of the FCM data as the Funcom dataset for this paper. The dataset we use is available in [Google_drive_tinyfuncom](https://drive.google.com/drive/folders/1JtNOigfzOjLGTkPhH9CPB__pvlT_9RVc?usp=share_link)

### Hybrid
Source paper: [Deep code comment generation with hybrid lexical and syntactical information](https://doi.org/10.1007/s10664-019-09730-9)

The source dataset is available in Google Drive: [dataset](https://drive.google.com/drive/folders/130liaynevaYo2AhNoFtadtc7uBS12_aW?usp=sharing)

We have de-duplicated this dataset, and the de-duplicated dataset is available in [Google_drive_hybrid_dedup](https://drive.google.com/drive/folders/110Vwl9bccZChRSaMm0uU7AuUMVPt_Cku?usp=share_link)

### Python
Source paper: [Improving automatic source code summarization via deep reinforcement learning](https://doi.org/10.1145/3238147.3238206)

The dataset is available in GitHub: [CODESCRIBE/data/python](https://github.com/GJCEXP/CODESCRIBE/tree/master/data/python)

We use this dataset directly, as there are no duplicates.

## Models
### Single-GRU
We put the code for this model in the directory **Single-GRU**

### Hybrid-Deepcom
Source paper: [Deep code comment generation with hybrid lexical and syntactical information](https://doi.org/10.1007/s10664-019-09730-9)

We put the code we reproduced for this model in the directory **Hybrid-Deepcom**
### Transformer
Source paper: [A Transformer-based Approach for Source Code Summarization](https://doi.org/10.18653/v1/2020.acl-main.449)

Source code in GitHub: [wasiahmad/NeuralCodeSum](https://github.com/wasiahmad/NeuralCodeSum)
### GTrans
Source paper: [Code comment generation based on graph neural network enhanced transformer model for code understanding in open-source software ecosystems](https://doi.org/10.1007/s10515-022-00341-1)

Source code in GitHub: [css518/GTrans](https://github.com/css518/GTrans)
