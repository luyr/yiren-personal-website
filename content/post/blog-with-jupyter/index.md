---
title: PyPose v0.6: The Imperative Programming Interface for Robotics
summary: IROS'2023 Workshop
authors: Zitong Zhan, Xiangfu Li, Qihang Li, Haonan He, Abhinav ,ey, Haitao Xiao, Yangmengfei Xu, Xiangyu Chen, Kuan Xu, Kun Cao, Zhipeng Zhao, Zihan Wang, Huan Xu, Zihang Fang, Yutian Chen, Wentao Wang, Xu Fang, Yi Du, Tianhao Wu, Xiao Lin, Yuheng Qiu, Fan Yang, Jingnan Shi, Shaoshu Su, Yiren Lu, Taimeng Fu, Karthik Dantu, Jiajun Wu, Lihua Xie, Marco Hutter, Luca Carlone, Sebastian Scherer, Daning Huang, Yaoyu Hu, Junyi Geng and Chen Wang
---


```python
from IPython.core.display import Image
Image('https://www.python.org/static/community_logos/python-logo-master-v3-TM-flattened.png')
```

    
![png](output_1_0.png)
    

```python
print("Welcome to Academic!")
```

    Welcome to Academic!

## Organize your notebooks

Place the notebooks that you would like to publish in a `notebooks` folder at the root of your website.

## Import the notebooks into your site

```bash
pipx install academic
academic import 'notebooks/**.ipynb' content/post/ --verbose
```

The notebooks will be published to the folder you specify above. In this case, they will be published to your `content/post/` folder.
