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

2. The training and testing pipeline is organized in run.ipynb (Jupyter Notebook).



## Figs

![](https://github.com/WangXin81/ORENet2.0/ORENet.jpg)

## Datasets:

HRSC2016: 
[https://sites.google.com/site/hrsc2016/]


DOTA v1.0: 
[https://captain-whu.github.io/DOTA/index.html]



## Environments

1. Ubuntu 18.04
2. cuda 10.2
3. pytorch 1.9.0
4. python 3.7

