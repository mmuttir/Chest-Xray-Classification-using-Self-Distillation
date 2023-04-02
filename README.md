# XceptionNet with CBAM: Attention-based Image Classification

This repository contains an implementation of the XceptionNet architecture enhanced with Convolutional Block Attention Module (CBAM) for improved image classification. The main goal of this project is to leverage the power of XceptionNet and enhance its capabilities by incorporating attention mechanisms through CBAM. This implementation is designed to be easy to use and extend.

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Customization](#customization)
6. [Results](#results)
7. [Citation](#citation)
8. [License](#license)

## Introduction

[XceptionNet](https://arxiv.org/abs/1610.02357) is a powerful and efficient deep learning architecture for image classification tasks. It employs depthwise separable convolutions to significantly reduce the number of parameters without sacrificing performance. [CBAM](https://arxiv.org/abs/1807.06521) (Convolutional Block Attention Module) is an attention mechanism that enhances the feature representation of CNNs by focusing on important spatial and channel-wise information. By combining XceptionNet with CBAM, we aim to improve the model's performance on various image classification tasks.

This implementation is built using Tensorflow and supports multi-GPU training.

