# Vision-Transformer-papers

This repository contains a (non-exhaustive) overview of follow-up works based on the original [Vision Transformer (ViT)](https://arxiv.org/abs/2010.11929) by Google. Feel free to open a PR to add more papers!

## Distillation:
* DeiT (Data-efficient Image Transformers): https://arxiv.org/abs/2012.12877 
* Efficient Vision Transformers via Fine-Grained Manifold Distillation: https://arxiv.org/abs/2107.01378

## New pre-training objectives:
- self-supervised:
    * BEiT (BERT Pre-Training of Image Transformers): https://arxiv.org/abs/2106.08254
    * DINO (Emerging Properties in Self-Supervised Vision Transformers): https://arxiv.org/abs/2104.14294 
    * MoBY (Self-Supervised Learning with Swin Transformers): https://arxiv.org/abs/2105.04553
    * EsViT (Efficient self-supervised Vision Transformers): https://arxiv.org/abs/2106.09785
- supervised:
    * Token Labeling for Better Training Vision Transformers: https://arxiv.org/abs/2104.10858 
    * Vision Transformers with Patch Diversification: https://arxiv.org/abs/2104.12753

## New pre-training tricks, techniques:
* Scaling Vision Transformers: https://arxiv.org/abs/2106.04560
* Vision Transformers with Patch Diversification: https://arxiv.org/abs/2104.12753
* Billion-Scale Pretraining with Vision Transformers for Multi-Task Visual Representations: https://arxiv.org/abs/2108.05887
* How to train your ViT? Data, Augmentation, and Regularization in Vision Transformers: https://arxiv.org/abs/2106.10270
* When Vision Transformers Outperform ResNets without Pretraining or Strong Data Augmentations (SAM optimizer): https://arxiv.org/abs/2106.01548

## Architectural changes:
- Combining convolution with self-attention:
    * CvT (Introducing convolutions to Vision Transformers): https://arxiv.org/abs/2103.15808
    * ConViT (Improving Vision Transformers with Soft Convolutional Inductive Biases): https://arxiv.org/abs/2103.10697
    * CMT (Convolutional Neural Networks Meet Vision Transformers): https://arxiv.org/abs/2107.06263 
    * LeViT (A Vision Transformer in ConvNet's Clothing for Faster Inference): https://arxiv.org/abs/2104.01136 
    * Co-Scale Conv-Attentional Image Transformers (CoaT): https://arxiv.org/abs/2104.06399
    * Visformer (The Vision-friendly Transformer): https://arxiv.org/abs/2104.12533
    * CCT (Escaping the Big Data Paradigm with Compact Transformers): https://arxiv.org/abs/2104.05704 
    * Refiner (Refining Self-attention for Vision Transformers): https://arxiv.org/abs/2106.03714 
- Others:
    * PiT (Rethinking Spatial Dimensions of Vision Transformers): https://arxiv.org/abs/2103.16302
    * xCiT (Cross-Covariance Image Transformer): https://arxiv.org/abs/2106.09681 
    * EsViT (Efficient self-supervised Vision Transformers): https://arxiv.org/abs/2106.09785
    * Token-to-token ViT (Training ViT from scratch on ImageNet): https://arxiv.org/abs/2101.11986 
    * DeepViT (Towards Deeper Vision Transformer): https://arxiv.org/abs/2103.11886
    * PVT (Pyramid Vision Transformer: A Versatile Backbone for Dense Prediction without Convolutions): https://arxiv.org/abs/2102.12122
    * PVTv2 (Improved Baselines with Pyramid Vision Transformer): https://arxiv.org/abs/2106.13797
    * Wider Vision Transformer (Go Wider Instead of Deeper): https://arxiv.org/abs/2107.11817
    * CaiT (Going Deeper with Image Transformers): https://arxiv.org/abs/2103.17239 
    * CrossViT (Cross-Attention Multi-Scale Vision Transformer for Image Classification): https://arxiv.org/abs/2103.14899
    * Twins-CVT (Spatial Attention in Vision Transformers): https://arxiv.org/abs/2104.13840 
    * LIT (Less is More: Pay Less Attention in Vision Transformers): https://arxiv.org/abs/2105.14217
    * TnT (Transformer-in-Transformer): https://arxiv.org/abs/2103.00112
    * Dynamic Vision Transformer: https://arxiv.org/abs/2105.15075
    * Swin Transformer (Hierarchical Vision Transformer using Shifted Windows): https://arxiv.org/abs/2103.14030 
    * Shuffle Transformer (Rethinking Spatial Shuffle for Vision Transformer): https://arxiv.org/abs/2106.03650 
    * NesT (Aggregating Nested Transformers): https://arxiv.org/abs/2105.12723
    * Long-Short Transformer (Efficient Transformers for Language and Vision): https://t.co/V8qKUkVH1c?amp=1 
    * DynamicViT (Efficient Vision Transformers with Dynamic Token Sparsification): https://arxiv.org/abs/2106.02034 
    * Dynamic Transformer (Dynamic Vision Transformers with Adaptive Sequence Length): https://arxiv.org/abs/2105.15075 
    * PS-ViT (Vision Transformer with Progressive Sampling): https://arxiv.org/abs/2108.01684
    * RegionViT (Regional-to-Local Attention for Vision Transformers): https://arxiv.org/abs/2106.02689 
    * Focal Transformer (Focal Self-attention for Local-Global Interactions in Vision Transformers): https://arxiv.org/pdf/2107.00641.pdf 
    * kVT (k-NN Attention for Boosting Vision Transformers): https://arxiv.org/abs/2106.00515
    * Robust Vision Transformer: https://arxiv.org/abs/2105.07926 
    * Glance-and-Gaze Vision Transformer: https://arxiv.org/abs/2106.02277
    * Feature Fusion Vision Transformer: https://arxiv.org/abs/2107.02341 
    * Augmented Shortcuts for Vision Transformers: https://arxiv.org/abs/2106.15941
    * CrossFormer (A Versatile Vision Transformer Based on Cross-scale Attention): https://arxiv.org/abs/2108.00154
    * CSWin Transformer (A General Vision Transformer Backbone with Cross-Shaped Windows): https://arxiv.org/pdf/2107.00652.pdf
    * Evo-ViT (Slow-Fast Token Evolution for Dynamic Vision Transformer): https://arxiv.org/abs/2108.01390
    * PSViT (Better Vision Transformer via Token Pooling and Attention Sharing): https://t.co/OOnONItfnX?amp=1
    * ImageRPE (relative position encodings) for Vision Transformers: https://arxiv.org/abs/2107.14222
    * What makes for Hierarchical Vision Transformer? https://arxiv.org/abs/2107.02174

## Investigations of the inner workings (cfr. BERTology):

* Are Convolutional Neural Networks or Transformers more like human vision? https://arxiv.org/abs/2105.07197
* Do Vision Transformers See Like Convolutional Neural Networks? https://arxiv.org/abs/2108.08810
* What makes for Hierarchical Vision Transformer? (Survey on Swin + ShuffleTransformer): : https://arxiv.org/abs/2107.02174
* Intriguing Properties of Vision Transformers: https://arxiv.org/abs/2105.10497
* Exploring Corruption Robustness: Inductive Biases in Vision Transformers and MLP-Mixers: https://arxiv.org/abs/2106.13122

## Applying ViT to other domains besides image classification:

* YOLOS (object detection): https://arxiv.org/abs/2106.00666
* ViTGAN (GANs): https://arxiv.org/abs/2107.04589 
* SegFormer (semantic segmentation): https://arxiv.org/abs/2105.15203
* Feature Fusion Vision Transformer (Fine-Grained Visual Categorization): https://arxiv.org/abs/2107.02341
