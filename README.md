# Scientific paper recommendation
The implementation and evaluation of the scientific paper recommendation system employing Alternating Least Squares (ALS), Latent Matrix Factorization (LMF), and based on graph convolutional network (PinSage).
## Dataset:

The data used is the [citation network dataset](https://www.aminer.cn/citation) DBLP v11 (4m papers + 36m authors). For a practical training, we just use a tiny subset of this huge dataset, which only contains [CCF A conferences and journals on AI area](https://www.ccf.org.cn/xspj/rgzn/)(3k papers + 5k authors). 

The sepcific dataset and other cache files can be downloaded in [OneDrive](https://1drv.ms/f/s!AtiMpA7HPe0QhcsNRDjt73z2suXsIg)

## Environment:

* Python 3.6
* Pytorch 1.0
* [DGL 0.3(beta)](https://www.dgl.ai/)
* Spacy + fastText
* CUDA supported (For GCN model training)