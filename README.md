# Image-Colorization-with-U-Net-and-GAN-Tutorial


One of the most exciting applications of deep learning is colorizing black and white images. This task needed a lot of human input and hardcoding several years ago but now the whole process can be done end-to-end with the power of AI and deep learning. You might think that you need huge amount of data or long training times to train your model from scratch for this task but in the last few weeks I worked on this and tried many different model architectures, loss functions, training strategies, etc. and finally developed an efficient strategy to train such a model, using the latest advances in deep learning, on a rather small dataset and with really short training times. In this article, I'm going to explain what I did to make this happen, including the code!, and the strategies that helped and also those that were not useful. Before that, I will explain the colorization problem and a give you a short review of what has been done in recent years. 

This  tutorial is based on Stanford's computer vision course. Here you can find their full projects on this github repository and access the courses:

[Link to the github repository](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix.git)

![gif](https://github.com/PouyaSonej/Image-Colorization-with-U-Net-and-GAN-Tutorial/blob/8572d7d0ec0fcf78594f555bfa9f15b4765f8e2a/data/anim_compare.gif)
