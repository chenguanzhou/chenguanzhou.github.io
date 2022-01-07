title: "CDTStudio项目开发计划"
date: 2016-01-21 10:37:24
---

长期目标
=================
* 成为国内外知名的高分辨率遥感影像分析处理开源框架
* 让项目成员相互交流，相互提高
* <del>学习当年的武大吉奥让ArcGIS降价的精神，让eCognition降价（当然也要吸取吉奥失败的教训）</del>
* <del>让MFC安心去死吧</del>

算法、插件开发目标
=================
分割算法
-----------------
* [基于图论最小生成树的分割算法](http://www.cnki.net/KCMS/detail/detail.aspx?dbcode=CDFD&QueryID=3&CurRec=4&dbname=CDFD0911&filename=1011065738.nh&urlid=&yx=&uid=WEEvREcwSlJHSldTTGJhYkhndWVFSVlGRUliRkh1NnU0WGFaeW5vUzdnZnhQQnZWN2prM0gyY2Y3TzJuMnBCU1JuND0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MjYyOTk4ZVgxTHV4WVM3RGgxVDNxVHJXTTFGckNVUkx5Zlp1UnVGeXprVWJ2TlZGMjZIN08rRzliUHA1RWJQSVI=) （已实现）
* Mean-Shift分割算法
* 基于图论标准割算法
* 分水岭分割算法
* 超像素分割算法
* ......

属性计算、特征提取算法
------------------
* 基于光谱的特征提取（已实现）
* 基于形状/几何的特征提取（已实现）
* 基于GLCM/GLDV纹理特征提取（已实现）
* 基于小波纹理特征提取
* 基于Markov随机场/条件随机场的纹理特征提取
* ......

监督分类、机器学习算法
------------------
* 最大似然法（已实现）
* K-Nearest-Neighbor（已实现）
* 支持向量机/自动阈值支持向量机（已实现）
* 随机树/随机森林（已实现）
* 深度AutoEncoder/波尔兹曼机/置信网络
* ......

半自动地物轮廓提取算法
-----------------
* Snakes (Active Contour Model) （已实现）
* ......

自动阈值算法
-----------------
* Otsu（已实现）
* Tsai
* Kapur
* Kittler's
* Hamin fuzzy
* ......

基于像素变化检测算法
-----------------
* 差值法（已实现）
* 比值法
* 光谱角距离法
* 基于NDVI的算法
* ......

