# Seq2seq-pytorch
  
### Sequence to Sequence Architecture in Pytorch  
[<img src="https://github.com/gentaiscool/end2end-asr-pytorch/raw/master/img/pytorch-logo-dark.png" height=18>](https://pytorch.org/) <img src="https://img.shields.io/badge/License-Apache--2.0-yellow" height=20>
  
### [**Documentation**](https://sooftware.github.io/pytorch-seq2seq/)
  
`Seq2seq-pytorch` is a framework for attention based sequence-to-sequence models implemented in [Pytorch](https://pytorch.org/).  
The framework has modularized and extensible components for seq2seq models, training and inference, checkpoints, etc.  
  
## Intro
Seq2seq turns one sequence into another sequence. It does so by use of a recurrent neural network (RNN) or more often LSTM or GRU to avoid the problem of vanishing gradient. The context for each item is the output from the previous step. The primary components are one encoder and one decoder network. The encoder turns each item into a corresponding hidden vector containing the item and its context. The decoder reverses the process, turning the vector into an output item, using the previous output as the input context.
   
<img src="https://cdn-images-1.medium.com/max/1000/1*QWVZX2bVBK5tHOgDJK38aA.png" width=800>
  


## Installation
This project recommends Python 3.6 or higher.   
I recommend creating a new virtual environment for this project (using virtualenv or conda).  

### Prerequisites
  
* Numpy: `pip install numpy` (Refer [here](https://github.com/numpy/numpy) for problem installing Numpy).
* PyTorch: Refer to [PyTorch website](http://pytorch.org/) to install the version w.r.t. your environment.
  
## Troubleshoots and Contributing
If you have any questions, bug reports, and feature requests, please [open an issue](https://github.com/sh951011/PyTorch-Seq2seq/issues) on Github.  
or Contacts sh951011@gmail.com please.
  
I appreciate any kind of feedback or contribution.  Feel free to proceed with small issues like bug fixes, documentation improvement.  For major contributions and new features, please discuss with the collaborators in corresponding issues.  

### Code Style
I follow [PEP-8](https://www.python.org/dev/peps/pep-0008/) for code style. Especially the style of docstrings is important to generate documentation.  
  
## Reference
[[1]   IBM pytorch-seq2seq](https://github.com/IBM/pytorch-seq2seq)   
[[2]   Pytorch-End-to-End-Korean-Speech-Recognition](https://github.com/sooftware/End-to-End-Korean-Speech-Recognition)      
[[3]   RNN Language Model](https://github.com/sooftware/char-rnnlm)      
  
## Citing
```
@github{
  title={pytorch-seq2seq},
  author={Soohwan Kim},
  publisher={github},
  docs={https://sooftware.github.io/pytorch-seq2seq/},
  url={https://github.com/sooftware/pytorch-seq2seq},
  year={2020}
}
```
