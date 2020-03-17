# <img src="https://github.com/aksnzhy/dgl/blob/master/apps/kg/img/logo.png" width = "400"/>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](./LICENSE)

DGL-KE is a igh performance, easy-to-use, and scalable package for learning large-scale knowledge graph embeddings. The package is implemented with Python on top of [Deep Graph Library (DGL)](https://github.com/dmlc/dgl) and developers can run DGL-KE on CPU machine, GPU machine, as well as clusters with a number of popular models, including [TransE](https://www.utc.fr/~bordesan/dokuwiki/_media/en/transe_nips13.pdf), [TransR](file:///Users/alex/Downloads/9571-44393-1-PB.pdf), [RESCAL](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.383.2015&rep=rep1&type=pdf), [DistMult](https://arxiv.org/abs/1412.6575), [ComplEx](http://proceedings.mlr.press/v48/trouillon16.pdf), and [RotatE](https://arxiv.org/pdf/1902.10197.pdf).

<p align="center">
  <img src="https://github.com/aksnzhy/dgl/blob/master/apps/kg/img/dgl_ke_arch.PNG" alt="DGL-ke architecture" width="600">
  <br>
  <b>Figure</b>: DGL-KE Overall Architecture
</p>

Get started with our [tutorials](https://docs.dgl.ai)!

## Installation

DGL-KE is built in Python (version 3.6 or later) and relies on [DGL](https://github.com/dmlc/dgl) (at least version 0.4.2). The package can run with both [Pytorch](https://pytorch.org/) and [MXNet](https://mxnet.apache.org/). For Pytorch, it works with Pytorch v1.2 or newer. For MXNet, it works with MXNet 1.5 or newer.

#### Using anaconda

```
conda install -c dglteam xxx
```

#### Using pip

```
pip install xxx
```

#### Build from source

Refer to the guide [here](https://docs.dgl.ai/install/index.html#install-from-source).

## Performance and Scalability

DGL-KE is designed for learning at scale, and it introduces various novel optimizations that accelerate training on knowledge graphs with millions of nodes and billions of edges. The benchmark results represent a 2×∼5× speedup over the best competing approaches.

## License

This project is licensed under the Apache-2.0 License.

