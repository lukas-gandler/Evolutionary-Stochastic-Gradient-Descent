# Evolutionary-Stochastic-Gradient-Descent
Experiments using ESGD on regular and momentum ResNets. As datasets we used CIFAR10 and smallNORB.

## ESGD algorithm
The ESGD algorithm was proposed by Cui, Xiadong, et al.

```
Cui, Xiaodong, et al. 
Evolutionary stochastic gradient descent for optimization of deep neural networks.
Advances in neural information processing systems 31 (2018).
```

## Momentum ResNets
Momentum ResNets were developed by Sander, et al. In order to work with these kinds of networks we used the momentumnet library, more information can be found under https://github.com/michaelsdr/momentumnet

```
Michael E. Sander, Pierre Ablin, Mathieu Blondel, Gabriel Peyré
Momentum Residual Neural Networks
Proceedings of the 38th International Conference on Machine Learning, PMLR 139:9276-9287
https://arxiv.org/abs/2102.07870
```

## Networks and datasets

The ResNets implementation was taken from akamaster. More information under https://github.com/akamaster/pytorch_resnet_cifar10/blob/master/resnet.py

The wrapper for smallNORB was created by ndrplz. More information under https://github.com/ndrplz/small_norb


