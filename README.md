一个三七种植面积遥感提取工具，还可以用于Landsat、Sentinel2等Vis-NIR影像的水体提取。

参考文献：
  （1）[SNRI: A Signed Normalized Range Index for Remote Sensing of Panax Notoginseng Plantations](https://ieeexplore.ieee.org/document/10475315/) 
  
  （2）[一种基于多光谱卫星遥感影像的三七种植面积计算方法](https://kns.cnki.net/kcms2/article/abstract?v=smPsKIJgVaD0YzfShAMWFLWV9e-2KWKO9irK9JZdWz3Ar-o002jXXwNnDJSzGiK3xH-J9vR9HrQejWA1I0djCOyO-YpTt4fjKRAELRyDj19Lep3bQEOUy5yZm06UXBEydJMNcpLUrTI=&uniplatform=NZKPT&language=CHS)

平台：ENVI5.6+

输入数据：
  （1）多光谱反射率影像（Landsat-30m/Sentinel2-10m）
  （2）DEM （可选）
  （3）地物光谱库（用于混合像元分解，可选）

输出结果：
  （1）水体和三七面积的可视化
  （2）提取结果栅格影像ENVI标准格式
  （3）面积统计文本（可选）

拓展工具界面：
![Panax_Notoginseng_ENVI56_extension](https://github.com/xiexiangjian/ENVI56_Panax_notoginseng/assets/58714940/fa0eacb8-a68a-4d10-a766-3bf5bb5dcc19)


