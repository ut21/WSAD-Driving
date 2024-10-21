## WS-DoTA

WS-DoTA (weakly supervised detection of traffic anomaly) is an extension of the [DoTA dataset](https://arxiv.org/pdf/2004.03044) to make it consistent with the weakly supervised training setup. The figure shows the structure of the dataset:

![alt text](images/docs.jpg)

The normal videos (without anomaly) in the train split are taken from the [$D^2$-City dataset](https://arxiv.org/abs/1904.01975) 

The instructions to download the two datasets can be found [here](https://drive.google.com/drive/folders/1_WzhwZC2NIpzZIpX7YCvapq66rtBc67n) for DoTA and [here](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://www.scidb.cn/en/detail%3FdataSetId%3D804399692560465920&ved=2ahUKEwiFg-jX55-JAxUMVqQEHbcpHmEQr-IDegQIFxAG&usg=AOvVaw3m_8jcPmkd_WWPp2c7JdDC) from $D^2-City$.

The videos present in each split are given in the directory ```dataset``` along with the ground truth annotations, and frame counts for test and train splits