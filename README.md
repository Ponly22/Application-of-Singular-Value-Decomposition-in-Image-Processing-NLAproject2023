# Application-of-Singular-Value-Decomposition-in-Image-Processing-NLAproject
This repository consist of the project at NLA2023 course at Skoltech.

## Table of Contents 

 - [Overall](#overall)
 - [Quickstart](#quickstart)
 - [Reference](#reference) 
 - [Credit](#credit)

## Overall 

-   Image denoising using SVD

  
  [![dict.png](https://i.postimg.cc/xCwZQgq7/dict.png)](https://postimg.cc/zbk7SCCS)

-   Image compression using SVD

  
  [![photo-2023-12-19-00-37-31.jpg](https://i.postimg.cc/T3R5QDTv/photo-2023-12-19-00-37-31.jpg)](https://postimg.cc/zVcfG3Lx)


## Quickstart

There are 4 main steps to build and test the results.

 1. Install necessary's packages 
    ``` bash 
    import pandas as pd
    import matplotlib.pyplot as plt
    from matplotlib.pyplot import imsave
    import numpy as np
    from imageio import imread
    import scipy
    import time
    tik = time.time()
    import os
    ```
 2. Compute SVD
    ``` bash 
    u, s, vh = np.linalg.svd(img, full_matrices=False)
    ```
 3. Build the specific image processing functions 
     such as compression.
    here is the code:
    https://github.com/Ponly22/Application-of-Singular-Value-Decomposition-in-Image-Processing-NLAproject/tree/compression_images
   
 5. Show image output
    ``` bash 
    ax.imshow(img)
    ```
## Reference 

The source that we use and read to make our project are :

1. Pandey, Jay Prakash and Singh Umrao, Lokendra, Digital Image Processing using Singular Value Decomposition (March 11, 2019). Proceedings of 2nd International Conference on Advanced Computing and Software Engineering (ICACSE) 2019, Available at SSRN: https://ssrn.com/abstract=3350278 or  http://dx.doi.org/10.2139/ssrn.3350278.
2. Misko, Oleh & Veseliak, Valerii. (2019). Singular Value Decomposition in image noise filtering. 10.13140/RG.2.2.18734.97601, Available at Researchgate: https://www.researchgate.net/publication/333199772_Singular_Value_Decomposition_in_image_noise_filtering. 
3. Rui Wang, Wanxiong Cai, Zaitang Wang, A New Method of Denoising Crop Image Based on Improved SVD in Wavelet Domain (August 26,2021). Security and Communication Networks, vol. 2021, Article ID 9995813, 11 pages, 2021. https://doi.org/10.1155/2021/9995813
4.. J. Redford and X. Li, "Exploration of SVD for Image Compression and Time Series Processing," 2020 IEEE MIT Undergraduate Research Technology Conference (URTC), Cambridge, MA, USA, 2020, pp. 1-4, doi: 10.1109/URTC51696.2020.9668891.

## Credit

Team members:

1. Addisu Zena
2. Anna Ermakova
3. Pattapon Tanankakorn
