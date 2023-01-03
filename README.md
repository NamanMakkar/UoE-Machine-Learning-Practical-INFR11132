# UoE-Machine-Learning-Practical-INFR11132
This repository contains the code and reports for the course INFR11132 Machine Learning Practical. Overall Mark Achieved - 75%

Coursework 3 features the final project for which the novel model architecture MixConv-EfficientNeSt-Ghost (ME-NeSt-Ghost) was introduced. It was built to improve upon the EfficientNetV2 family of CNNs in image classification tasks with the help of a combination of mixed-depthwise convolutions, split attention modules and ghost convolutions. The ME-NeSt-Ghost was more parameter efficient than the EfficientNetV2 while providing comparable or even better results on the CIFAR-100 dataset

![The novel MixConv-Squeeze-Excitation-Ghost Block](mixconv-se-ghost.png)

![The novel MixConv-Split-Attention Block](mixconv-splatt.png)

![Details of the ME-NeSt-Ghost-S model architecture](me-nest-ghost-s.png)

![Details of the ME-NeSt-Ghost-M model architecture](me-nest-ghost-m.png)

![Details of the ME-NeSt-Ghost-L model architecture](me-nest-ghost-l.png)

![Details of the ME-NeSt-Ghost-XL model architecture](me-nest-ghost-xl.png)

![Graph comparing the ME-NeSt-Ghost model architectures with the EfficientNetV2 model architectures on the CIFAR 100 dataset](acc-vs-parameters.pdf)

![Table comparing the ME-NeSt-Ghost model architectures with the EfficientNetV2 model architectures on the CIFAR 100 dataset](model-performance.png)