# OCR-DATA
## OCR常用的数据集
在这个代码仓库里，提供了常用的OCR检测和识别中的通用公开数据集的下载链接。并且提供了json标签转成.txt标签的代码和转换好的.txt标签。

# 数据集介绍
| 数据集  |    数据介绍    |     标注格式 |        下载地址 |
| ---         |     ---      |          --- |           --- |
| SVT | 语言: 英文 | |  [下载链接](http://vision.ucsd.edu/~kai/svt/)
| IIIT5k | 语言: 英文 | |  [下载链接](https://github.com/gsy-cv/IIIT5K)
| ICDAR_2013|语言: 英文  train:229  test:233| x1 y1 x2 y2 text  |  [下载链接](https://rrc.cvc.uab.es/?ch=2&com=downloads).  |
| ICDAR_2015|语言: 英文  train:1000  test:500|x1,y1,x2,y2,x3,y3,x4,y4,text  | [下载链接](https://rrc.cvc.uab.es/?ch=4&com=downloads).  |
| ICDAR2017-MLT| 语言: 混合  train:7200  test:1800  |   x1,y1,x2,y2,x3,y3,x4,y4,text   |  [下载链接](https://pan.baidu.com/s/1JADvSKXQ6wZ5wCgb6DYjmg). 提取码: z9ey |
| ICDAR2017-RCTW| 语言: 混合  train:8034  test:4229  |   x1,y1,x2,y2,x3,y3,x4,y4,<识别难易程度>,text  | [下载链接](https://rctw.vlrlab.net/dataset/) |
| 天池比赛2018| 语言: 混合  train:10000  test:10000      |    x1,y1,x2,y2,x3,y3,x4,y4,text    |  [检测](https://tianchi.aliyun.com/competition/entrance/231684/introduction)。 [识别](https://tianchi.aliyun.com/competition/entrance/231684/introduction) |
| ICDAR2019-MLT| 语言: 混合  train:10000  test:10000    |   x1,y1,x2,y2,x3,y3,x4,y4,语言类别,text    |  [下载链接](https://pan.baidu.com/s/1VDAvnvNvg8_SJa_vwEv5Ag). 提取码: xofo    |
| ICDAR2019-LSVT| 语言: 混合  train:30000  test:20000      |    json格式标签    |  [下载链接](https://rrc.cvc.uab.es/?ch=16) |
| ICDAR2019-ReCTS| 语言: 混合  train:20000  test:5000      |    json格式标签    |  [下载链接](https://rrc.cvc.uab.es/?ch=12&com=introduction) |
| ICDAR2019-ArT| 语言: 混合  train:5603  test:4563  |  json格式标签   |  [下载链接](https://rrc.cvc.uab.es/?ch=14) |
| Synth800k| 语言: 英文  80k    |   基于字符标注    |  [下载链接](http://www.robots.ox.ac.uk/~vgg/data/scenetext/)   |
| 360万中文数据集| 语言: 中文  360k      |    每张图片由10个字符构成    |   [下载链接](https://pan.baidu.com/s/1QkI7kjah8SPHwOQ40rS1Pw).  提取码:lu7m |
| 中文街景数据集CTW|   |   基于字符标注的中文街景图片   |  [下载链接](https://ctwdataset.github.io/) |
| 百度中文场景文字识别|  语言: 混合  32,285   |     |  [下载链接](https://aistudio.baidu.com/aistudio/datasetdetail/8429)  |
| MSRA-TD500|  语言: 中英文  Training:300  Test:200   |  .gt格式标签   |  [下载链接](http://www.iapr-tc11.org/mediawiki/index.php/MSRA_Text_Detection_500_Database_%28MSRA-TD500%29)  |
| Total-Text|  语言: 英文  Training:1255  Test:300   |     |  [下载链接](https://github.com/cs-chan/Total-Text-Dataset)  |
