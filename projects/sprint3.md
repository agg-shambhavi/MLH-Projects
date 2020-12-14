---
title: Sprint 3 Project
layout: page
---

<br>

# 🖼️ Sneaky Sketchers

## 🙋 What is Sneaky Sketchers?

Have you ever taken a photo in which there is some unneeded object in the background, ever taken a photo and someone just walked behind you, and now you feel the photo is not as good as it could have been? 📷

If so, worry not! This desktop application allows you to select the areas in a photo you want to remove by drawing on them. Once you're done, the app will erase the objects you drew on, and generate a new photo which would look as if those obejcts were never present! 🔥

You can also use this application for having some fun. Ever wondered how you would look without a moustache, or with spectacles? Or wondered how your face would like with different features? Well draw over your face, and let the app do the magic! 👦 👧

## 👨‍🏭 Who are we?

This project was built by [Shambhavi Aggarwal](https://github.com/agg-shambhavi), [Farhan Kiyani](https://github.com/farhan2742), [Yash Khare](https://github.com/yashk2000) and [Ridham Bhat](https://github.com/ridhambhat).

## 💻 What did we use?

Sneaky Sketchers is built completely in [Python](https://www.python.org/). We have created [Jupyter Notebooks](https://jupyter.org/) on [Google Colab](https://colab.research.google.com/) to train our models and the desktop app is built using [PyQt5](https://pypi.org/project/PyQt5/) 🐍

## 🔨 Installation

For setting up the desktop app, head over [here](https://github.com/yashk2000/SneakySketchers/tree/main/application).

## 💭 What we learned

- This was the first time Yash worked with PyQt and leanred a lot about making desktop apps with it. He also worked with PyTorch to this extent for the first time.
- Shambhavi had never worked with PyTorch before, and helped implement an entire research paper by NVIDIA in completely in PyTorch.
- Farhan did not have much experince with machine leanring, but he contributed to the project and learned a lot as well.

This project ended up being a kind of a research project for us since we spent quite a lot of our time reading the paper on Partial Convolutions by NVIDIA, understanding how it works, and implementing it. We found a Keras implementation which gave pretty good results. We understood the paper with the Keras code, and created a PyTorch implementation. Since this model is a bit large in size, we decided to go ahead with building a desktop application which can be used offline.

## 📕 Resources

- [https://github.com/MathiasGruber/PConv-Keras](https://github.com/MathiasGruber/PConv-Keras)
- "Image Inpainting for Irregular Holes Using Partial Convolutions", [https://arxiv.org/abs/1804.07723](https://arxiv.org/abs/1804.07723)

### Citation

```
@inproceedings{liu2018partialpadding,
   author    = {Guilin Liu and Kevin J. Shih and Ting-Chun Wang and Fitsum A. Reda and Karan Sapra and Zhiding Yu and Andrew Tao and Bryan Catanzaro},
   title     = {Partial Convolution based Padding},
   booktitle = {arXiv preprint arXiv:1811.11718},
   year      = {2018},
}
```

```
@inproceedings{liu2018partialinpainting,
   author    = {Guilin Liu and Fitsum A. Reda and Kevin J. Shih and Ting-Chun Wang and Andrew Tao and Bryan Catanzaro},
   title     = {Image Inpainting for Irregular Holes Using Partial Convolutions},
   booktitle = {The European Conference on Computer Vision (ECCV)},
   year      = {2018},
}
```

[Link to Github Repo](https://github.com/yashk2000/SneakySketchers) <br>
[Link to Demo Video](shorturl.at/xBDGO)
