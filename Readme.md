## **Image Inpainting Using Deep Learning** 

## Models 
## 1. Image Inpainting using gated convolution, spectral normalised GAN and Self-Attention 

### Dataset links

Places 2: [https://www.kaggle.com/mittalshubham/images256](https://www.kaggle.com/mittalshubham/images256)

Consists of images at different sizes 64 * 64, 128 * 128, 256 * 256

Mask Dataset: Trained with random free-form mask and random rectangular block.


### Instructions to run the files 

jupyter notebook CNNApproach/CNN_Inpaint.ipynb


## 2. Image Inpainting using Transformer GAN

### Dataset links

Celeba dataset: [https://www.kaggle.com/marupakanagaharshita/custom](https://www.kaggle.com/marupakanagaharshita/custom)

Consists of images at size 114 * 114. Created a random rectangular mask for each image during training. 

## 3. Model Checkpoints

Drive Link for Model Checkpoints: [https://drive.google.com/drive/folders/1OnXiTjIxYYrsfTB7cVV59QvDxhrtHFtM?usp=sharing](https://drive.google.com/drive/folders/1OnXiTjIxYYrsfTB7cVV59QvDxhrtHFtM?usp=sharing)

### Instructions to run the files 

jupyter notebook TransformerApproach/TransGAN_Inpaint.ipynb

- They contain the cells with training and testing sections.

```
@article{jiang2021transgan,
  title={TransGAN: Two Transformers Can Make One Strong GAN},
  author={Jiang, Yifan and Chang, Shiyu and Wang, Zhangyang},
  journal={arXiv preprint arXiv:2102.07074},
  year={2021}
}

@article{yu2018free,
  title={Free-Form Image Inpainting with Gated Convolution},
  author={Yu, Jiahui and Lin, Zhe and Yang, Jimei and Shen, Xiaohui and Lu, Xin and Huang, Thomas S},
  journal={arXiv preprint arXiv:1806.03589},
  year={2018}
}
```
