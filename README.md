# FashionMNIST CNN Image Classification

## Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify FashionMNIST clothing images into four selected categories:

- T-shirt/top
- Trouser
- Sneaker
- Bag

The model is trained using the standard FashionMNIST dataset downloaded automatically through `torchvision.datasets`.

After training, the model is also tested on 10 custom smartphone photographs of real-world objects. These images are stored in the GitHub repository and automatically downloaded into Google Colab using `git clone`.

The purpose of the project is to compare the model's performance on the standard FashionMNIST test data with its performance on real-world smartphone images.

---

## Classes

The project uses four classes from FashionMNIST:

| Class | FashionMNIST Label |
|---|---:|
| T-shirt/top | 0 |
| Trouser | 1 |
| Sneaker | 7 |
| Bag | 8 |

These labels are mapped to four CNN output classes:

```text
0 → T-shirt/top
1 → Trouser
2 → Sneaker
3 → Bag
