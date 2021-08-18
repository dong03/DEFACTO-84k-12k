# DEFACTO-84k&12k
Txts in this directory provide the image lists of DEFACTO-84k and DEFACTO-12k used in [***MVSS-Net***](https://github.com/dong03/MVSS-Net). 

Each line in the txts contains:
```angular2html
img_path mask_path label
```
Note that:
+ You need to download [DEFACTO](https://defactodataset.github.io/) and [MSCOCO](https://cocodataset.org/) and obey their usage policies.
+ The dataset consists of four classes of images: *Authentic* images with label 0 and three kinds of manipulated images with label 1 for *CopyMove*, 2 for *Splicing* and 3 for *Inpainting*. 

Please refer to the [paper](https://arxiv.org/abs/2104.06832) and [code](https://github.com/dong03/MVSS-Net) for more details.