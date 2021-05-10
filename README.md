# SHDC
SHDC: A Method of Similarity Measurement Using Heat Kernel based on Denoising for Clustering scRNA-seq Data.
A Method of Similarity Measurement Using Heat Kernel based on Denoising for Clustering scRNA-seq Data (SHDC) was proposed for single cell clustering. SHDC denoised scRNA-seq datasets to obtain a more stable data structure and only a heat kernel was used to measure similarity between cells.

SHDC is implemented in Python 3 on HP Z840 work-station. In the implementation of SHDC, DCA module will be used. DCA is implemented in Python 3 using Keras and its TensorFlow  backend. So before using SHDC, make sure your computer has installed DCA module. In addition, SHDC uses Parallel Python (pp) module for CPU parallel computing, so it is necessary to ensure that pp module has been installed. The Python package scanpy is used in the calculation, so SHDC supports h5ad-formatted HDF5 files and anndata data format.

python: 3.6.5
DCA: 0.2.3
keras: 2.3.1
pp: 1.6.4.4
scanpy: 1.7.1
tensorflow: 1.15.0
If you have any problems, please contact me by email. 
Email:haiyun_wang_xju@163.com
