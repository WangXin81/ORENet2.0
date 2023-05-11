# ORENet


#### [Xin Wang](https://github.com/WangXin81)




## Usage
1. Data preparation:

```
dataset|——split_ss_dota
         |——trainval
           |——annfiles
             |——0001.txt
             |——0002.txt
             |——....
           |——images
             |——0001
             |——0002
             |——....
         |——test
           |——annfiles
             |——0001.txt
             |——0002.txt
             |——....
           |——images 
             |——0001
             |——0002
             |——....
         |——hrsc
           |——FullDataSet
             |——Annotations
               |——0001.xml
               |——0002.xml
               |——....
             |——AllImages
               |——0001
               |——0002
               |——....
           |——ImagesSets
             |——trainval.txt
             |——test.txt
         
```

2. Need to download pre-training [weight file](https://drive.google.com/uc?id=1GmJzzHRgp5SvmGa6uj6n4GpCuYRT5RE9&export=download) to work_dirs/re_resnet101_v2_c8_batch256-f248cc41.pth
3. The training and testing pipeline is organized in tools/train.py and tools/test.py.



## Figs
![image](https://github.com/WangXin81/ORENet2.0/blob/main/fig3.jpg)


## Datasets:

HRSC2016: 
[https://sites.google.com/site/hrsc2016/]


DOTA v1.0: 
[https://captain-whu.github.io/DOTA/index.html]



## Environments

1. Ubuntu 
2. cuda 9.2+
3. pytorch 1.6+
4. python 3.7+

