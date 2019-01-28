# Pre-Training Buys Robustness and Uncertainty

This repository contains the essential code for the paper [_Using Pre-Training Can Improve Model Robustness and Uncertainty_](https://people.eecs.berkeley.edu/~hendrycks/).

Requires Python 3+ and PyTorch 0.4.1+.

<img align="center" src="table_adv.png" width="750">

## Abstract

Tuning a pre-trained network is commonly thought to improve data efficiency. However, Kaiming He et al. have called into question the utility of pre-training by showing that training from scratch can often yield similar performance, should the model train long enough. We show that although pre-training may not improve performance on traditional classification metrics, it does provide large benefits to model robustness and uncertainty. Through extensive experiments on label corruption, class imbalance, adversarial examples, out-of-distribution detection, and confidence calibration, we demonstrate large gains from pre-training and complementary effects with task-specific methods. We show approximately a 30% relative improvement in label noise robustness and a 10% absolute improvement in adversarial robustness on CIFAR-10 and CIFAR-100. In some cases, using pre-training without task-specific methods surpasses the state-of-the-art, highlighting the importance of using pre-training when evaluating future methods on robustness and uncertainty tasks.


## Citation

If you find this useful in your research, please consider citing:

    @article{hendrycks2019pretraining,
      title={Using Pre-Training Can Improve Model Robustness and Uncertainty},
      author={Hendrycks, Dan and Lee, Kimin and Mazeika, Mantas},
      journal={arXiv},
      year={2019}
    }

