## koniq-PyTorch

A Pytorch reproduction of No-Reference Image Quality Assessment (NR-IQA) models trained on the KonIQ-10k dataset, proposed in the paper ["KonIQ-10k: An ecologically valid database for deep learning of blind image quality assessment"](https://arxiv.org/abs/1910.06180).

The code is based on [koncept512_train_test_py3.ipynb](https://github.com/subpic/koniq/blob/master/koncept512_train_test_py3.ipynb) provided in the [official repository](https://github.com/subpic/koniq).


# Download the KonIQ-10k dataset with ground truth:

```wget "http://datasets.vqa.mmsp-kn.de/archives/koniq10k_512x384.zip"```
```wget "https://github.com/subpic/koniq/blob/master/metadata/koniq10k_distributions_sets.csv"```
```unzip koniq10k_512x384.zip```  

# Train/test the optimal koncept512 model in the paper:
-Traing/test code in [koncept512_train_test_pytorch.ipynb](https://github.com/ZhengyuZhao/koniq-PyTorch/blob/master/koncept512_train_test_pytorch.ipynb).

-The [pre-trained model](https://surfdrive.surf.nl/files/index.php/s/oeGv7wEyyMwwbIO) is also available.
