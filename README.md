# Semi-Supervised-Semantic-Segmentation-Activation-Map-Interpolation-PyTorch

This repository contains the code for the paper [Semi-Supervised Semantic Segmentation with Activation Map Interpolation]. 
We are still firming up some of the benchmarking code, but the core code is available for use. Paper will soon be available for citation in arXiv. 

We propose a method that can take a small labeled set of data, and a larger set of unlabeled data, to produce fine-grained defect segmentation that comes close to the performance of fully supervised methods. Our model tha is fully-convolutional, and has a twin-branch encoder-decoder formulation. The model is derived from consistency regularization and interpolation consistency training. The consistency constraint is enforced at the level of the decoder outputs, such that the outputs from the interpolated inputs are the same as the output obtained from the unlabeled samples, interpolated after the predictions are made. Experiments on the NEU metallic surface defect, CrackForest, and GD X-Ray weld defects datasets show that the proposed model is able to obtain competitive performance compared to fully supervised baselines with limited labeled data. The experiments also compared results with other benchmark models and comparable results, with some exceeding the current benchmark metrics are obtained.

