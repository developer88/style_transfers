# Style Transfer using PyTorch

ℹ️ 2 simple notebooks with [Style Transfer](https://arxiv.org/abs/1508.06576) by Leon A. Gatys, Alexander S. Ecker, Matthias Bethge based on [official PyTorch](https://pytorch.org/tutorials/advanced/neural_style_tutorial.html) and [Udacity](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/style-transfer) tutorials.

During my Deep Learning course I tried to play around with Style Transfer first based on Udacity's example and then on PyTorch's one. Even though they both are based on the same paper by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge, there are some differences though in how they implement and calculate `gram matrxi`, `content` and `style` loss.

⚠️ I left all the comments behind. You can read them in the links provided above. Instead I enhanced the notebooks with some settings and some optimizations for Cuda that help you if you decide to play around with style transfer.

In both notebooks intermediate as well as final results will be saved into `images` folder that will be created automatically in this repo.

## Usage

* Add `source.jpg` and `style.jpg` to the root of this repo
* create a conda environment `conda create --name <env> --file requirements.txt` with Python 3.7 (did not tested on > 3.7).
* open a notebook you interested in and adjust the settings on the second cell. 
* run all the cells.

## Licence

Read it [here](LICENCE).
