# ZynqNet: A FPGA-Accelerated Embedded Convolutional Neural Network

This repository contains the results from my Master Thesis.

## Report
The report includes
- an overview and detailed analysis of many popular CNN architectures for Image Classification (AlexNet, VGG, NiN, GoogLeNet, Inception v.X, ResNet, SqueezeNet)
- a detailed description of the (*Netscope* CNN analysis tool)[https://github.com/dgschwend/netscope] found here: (dgschwend/netscope)[https://github.com/dgschwend/netscope]
- an overview of CNN analysis and optimization techniques
- a detailed report on the design and implementation of the FPGA-based accelerator

## ZynqNet CNN Architecture for Image Classification on ImageNet (ILSVRC)
The fully trained CNN with .prototxt network description and pretrained weights can be found under "prototxt"

## Netscope CNN Analyzer
The CNN analysis tool can be found in a separate repository here: (dgschwend/netscope)[https://github.com/dgschwend/netscope]

## High-Level Synthesis Source Code for FPGA accelerator
The C/C++ source code for building the FPGA accelerator using High-Level Synthesis (Vivado HLS) can be found under "HLS"
