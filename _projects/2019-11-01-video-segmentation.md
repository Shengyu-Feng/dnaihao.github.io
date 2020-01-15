---
title: "Video Segmentation"
collection: projects
permalink: /projects/2019-11-01-video-segmentation
start_date: 2019-11-01
end_date: 2019-12-01
location: "Ann Arbor, Michigan"
---

<img style="float: right;" src='/images/videoseg-sample.gif' width="50%">
Segmentation of the foreground in videos has many uses, ranging from background replacement to intruder detection. Many methods these days use deep learning, which while oftentimes having very good performance, suffers from the restriction of requiring a comprehensive dataset, as well as having a fixed input size. Other methods rely on the camera being stationary, which is a very significant limitation as well. Here, we propose a Python pipeline heavily inspired by [Tukey-Inspired Video Object Segmentation](https://arxiv.org/abs/1811.07958), which can perform in video from both static and dynamic cameras, while not using deep learning to preserve generalizability.

Most of the sample videos you see on this website are from the [DAVIS](https://davischallenge.org/) dataset.


<img style="float: right;" src='/images/videoseg-out.gif' width="50%" >
The GIF shows an example of the raw results from different algorithms we took and the generated consensus mask(the mask is shown in the bottom right block, the effect is shown in the second row, the first block).

More details for this project can be found at our project website: [project website](https://sites.google.com/umich.edu/video-segmentation/home). The link to our github repo of the source code: [github repo](https://github.com/bijustin/video-segmentation)