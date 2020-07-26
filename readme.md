# VizWiz Captions Demo

[VizWiz](https://vizwiz.org) is a project to develop algorithms to assist people who are blind. In particular, the [VizWiz Captions](https://vizwiz.org/tasks-and-datasets/image-captioning) dataset/challenge focuses on the problem of describing images taken by people who are blind.

A recent paper by Dr. Gurari et al, [Captioning Images Taken by People who are Blind](https://arxiv.org/abs/2002.08565), compares several algorithms on the VizWiz-Captions dataset. While the paper describes the relative performance of each algorithm, as measured by several common image captioning metrics, we are eager to see the results for ourselves.

We have created an easily runnable demo of an image captioning model trained on VizWiz data. The demo is based on the [AoANet](https://github.com/husthuaan/AoANet) architecture - there are already both [a model trained on the original MS-COCO dataset](https://drive.google.com/uc?export=download&id=199raguEM6yocl_DSbUxyXugzrjUEsVWW), as well as [a model trained on the VizWiz-Captions dataset](https://ivc.ischool.utexas.edu/VizWiz_final/caption/AoANet_VizWiz/log/log_aoanet_vizwiz_rl/model.pth).

This gives us an easy way to run an image through both models, and compare how a generic model would describe the image, compared with one trained on images taken by people who are blind.
