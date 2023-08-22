## 1. 介绍

上海市遥感影像与带高度的建筑物数据集

图片分辨率为**512px * 512px**，格式为`GeoTIFF`，文件后缀为`.tif`，带有坐标信息，坐标系为`EPSG3857`

6000多个样本，解压缩后数据量为9个G左右，建筑物覆盖率在10％以上，遥感影像来源Google地图

关于高度数据，是将每栋建筑的楼层数（floor） * 3 米

关于准确性，论文：[A deep learning method for building height estimation using high-resolution multi-view imagery over urban areas: A case study of 42 Chinese cities](https://www.researchgate.net/publication/353206769_A_deep_learning_method_for_building_height_estimation_using_high-resolution_multi-view_imagery_over_urban_areas_A_case_study_of_42_Chinese_cities) 中提到楼层数（floor）的**RMSE is 1.190**，并提到了**each floor is 3 m**的相关研究

文件夹`samples`下为示例数据，共14组，文件名字为`height_<x>_<y>`和`google_<x>_<y>`相对应

完整数据下载地址为：

 - 百度网盘链接: https://pan.baidu.com/s/1ZRTvOd2xFsWf7IOlHjpzoA?pwd=wgif 

一组示例数据如下图所示：

![image-20230821234503236](https://s2.loli.net/2023/08/22/lGyBP4ZD5rMOVxE.png)



## 2. 数据生产

数据集制作教程可参考：

- [基于QGIS生产建筑物高度与遥感影像数据集 - 当时明月在曾照彩云归 - 博客园 (cnblogs.com)](https://www.cnblogs.com/jiujiubashiyi/p/17647415.html)

如需定制其他城市、或者更为清晰的遥感影像，可以联系上述教程的作者

