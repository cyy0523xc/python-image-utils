# 常用图像工具库

python的图片工具库

## 相关项目

- https://github.com/ibbd-dev/python-ibbd-algo.git （暂时没有依赖该项目）

## Install 

```sh
# 安装依赖
pip3 install -r https://github.com/ibbd-dev/python-image-utils/raw/master/requirements.txt

# 安装
pip3 install git+https://github.com/ibbd-dev/python-image-utils.git
```

OR

```sh
pip3 install -r requirements.txt
python3 stepup.py install
```

## Usages

```python
from image_utils.convert import cv2_pil
```

## 文件说明

- image_utils/convert.py: 图像文件格式转换
- image_utils/box.py: 跟box框相关的函数
- image_utils/similary.py: 图像相似性函数
- image_utils/text_angle.py: 文本倾斜角度相关函数
- image_utils/text.py: 图像文字操作工具库，如往图像上输出中文字符等
- image_utils/line.py: 直线检测与识别
- image_utils/point.py: 点检测与识别
- image_utils/table.py: 表格相关工具库
- image_utils/box_cluster.py: box按行或者列进行聚类
- image_utils/data_augment.py: 图像数据增强
- image_utils/utils.py: 图像其他工具库
