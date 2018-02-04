# Introduction
This is the source code of our TCSVT paper "Learning Cross-Media Joint Representation with Sparse and Semisupervised Regularization", Please cite the following paper if you use our code.

Xiaohua Zhai, Yuxin Peng, and Jianguo Xiao, "Learning Cross-Media Joint Representation with Sparse and Semisupervised Regularization", IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), Vol. 24, No. 6, pp. 965-978 , Jun. 2014. 

# Usage
Run our script to train and test:
 
    JRL.m

The parameters are as follows:

    I_tr: the feature matrix of image instances for training, dimension : tr_n * d_i
    T_tr: the feature matrix of text instances for training, dimension : tr_n * d_t
    I_te: the feature matrix of image instances for test, dimension : te_n * d_i
    T_te: the feature matrix of text instances for test, dimension : te_n * d_t
    trainCat: the category list of data for training, dimension : tr_n * 1
    testCat: the category list of data for test, dimension : te_n * 1
    gamma: sparse regularization parameter, default: 1000
    sigma: mapping regularization parameter, default: 1000
    lambda: graph regularization parameter, default: 1
    miu: high level regularization parameter, default: 1
    k: kNN parameter, default: 100

XMedia dataset can be downloaded from [XMedia Dataset](http://www.icst.pku.edu.cn/mipl/xmedia)

For more information, please refer to our [paper](http://www.icst.pku.edu.cn/mipl/tiki-download_file.php?fileId=269)

# Related work
If you are interested in cross-media retrieval, check our paper:

Yuxin Peng, Xin Huang, and Yunzhen Zhao, "An Overview of Cross-media Retrieval: Concepts, Methodologies, Benchmarks and Challenges", IEEE Transactions on Circuits and Systems for Video Technology (TCSVT), 2017.

Visit our [Benchmark Website](http://www.icst.pku.edu.cn/mipl/xmedia) and [Laboratory Homepage](http://www.icst.pku.edu.cn/mipl) for more information.
