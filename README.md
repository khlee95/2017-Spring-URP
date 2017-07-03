# 2017-Spring-URP

This repository is workspace for 2017 Winter/Spring URP in KAIST.
Following works are advised in RCV lab in KAIST.

## installation

### install python3.5
```shell
conda updata conda
conda create -n py35 python=3.5 anaconda
activate py35
conda install opencv
deactivate source
```

### install pytorch
```shell
export CMAKE_PREFIX_PATH=[anaconda root directory]
conda install numpy pyyaml mkl setuptools cmake gcc cffi
conda install -c soumith magma-cuda80
pip install https://s3.amazonaws.com/pytorch/whl/cu80/torch-0.1.6.post22-cp35-cp35m-linux_x86_64.whl
pip install torchvision
```
