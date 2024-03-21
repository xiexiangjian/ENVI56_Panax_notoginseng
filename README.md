**标题**：一个三七种植面积遥感自动提取工具

**功能**：

该工具基于Vis-NIR影像反射率极差指数SNRI和极大值Max提取三七种植区（黑色遮阳网）；

在云南山区可以用来估算三七种植面积，还可以用于其他区域的**水体**和其他**低反射率极差地物**的提取。

**参考文献**：

  （1）[SNRI: A Signed Normalized Range Index for Remote Sensing of Panax Notoginseng Plantations](https://ieeexplore.ieee.org/document/10475315/) 

X. Xie, A. Samat, Y. He and Y. Jiang, "SNRI: A Signed Normalized Range Index for Remote Sensing of Panax Notoginseng Plantations," in IEEE Geoscience and Remote Sensing Letters, doi: 10.1109/LGRS.2024.3379196.

Abstract: Panax Notoginseng is a widely recognized medicinal herb in Chinese traditional medicine. Investigating the cultivation of P. notoginseng is crucial for ecological preservation and effective land management. In our study, we conducted an analysis of the spectral properties of P. notoginseng plantations along with various other land cover types. As a result, we have introduced a novel index called the Signed Normalized Range Index (SNRI), based on the maximum and minimum reflectance values across all bands of the multispectral imagery. Through experiments conducted on Landsat-8 OLI images obtained from Yunnan, China, we performed quantitative assessments of separability measurements. SNRI has shown great potential in enhancing the identification of P. notoginseng, with an average Jeffries-Matusita separability of 1.378 compared to other land covers. Furthermore, we conducted a comparative analysis of the SVM classification results using several spectral indices for dark target extraction. The comparison affirmed the superior performance of SNRI in accurately distinguishing P. notoginseng plantations from other land cover types. It is promising to explore the application of SNRI in remote sensing estimation and change monitoring of the P. notoginseng planting area, as well as other land covers with similar lower reflectance ranges.
  
  （2）[一种基于多光谱卫星遥感影像的三七种植面积计算方法](https://kns.cnki.net/kcms2/article/abstract?v=smPsKIJgVaD0YzfShAMWFLWV9e-2KWKO9irK9JZdWz3Ar-o002jXXwNnDJSzGiK3xH-J9vR9HrQejWA1I0djCOyO-YpTt4fjKRAELRyDj19Lep3bQEOUy5yZm06UXBEydJMNcpLUrTI=&uniplatform=NZKPT&language=CHS)

**平台**：ENVI5.6+

**输入数据**：

  （1）多光谱反射率影像（Landsat-TM/OLI、Sentinel2-10m）
  
  （2）DEM （可选）
  
  （3）地物光谱库（用于混合像元分解，可选）

**输出结果**：
  （1）水体和三七面积的可视化
  （2）提取结果栅格影像ENVI标准格式
  （3）面积统计文本（可选）

**拓展工具界面和运行示例**：

![Panax_Notoginseng_ENVI56_extension](https://github.com/xiexiangjian/ENVI56_Panax_notoginseng/assets/58714940/fa0eacb8-a68a-4d10-a766-3bf5bb5dcc19)

![image](https://github.com/xiexiangjian/ENVI56_Panax_notoginseng/assets/58714940/6382d785-e710-4f7e-8fba-ea26a57b1bde)

![image](https://github.com/xiexiangjian/ENVI56_Panax_notoginseng/assets/58714940/015233ab-8c18-430d-b00e-723583615ae0)

![image](https://github.com/xiexiangjian/ENVI56_Panax_notoginseng/assets/58714940/8f640b54-2ccb-4ace-997e-0d842fb1a5f2)
