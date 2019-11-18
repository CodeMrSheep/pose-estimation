# pose-estimation
人体姿态估计中的三维重建部分
主要包括：

1、给定不同角度摄像机拍摄的图像，运用sift方法提取图象中的特征点


2、给定不同角度摄像机拍摄的图像，运用传统三维重建方法进行三维重建

->1 由特征点求解本质矩阵

->2 decompose本质矩阵得到R、T

->3 用三角测距法进行三维重建（运用matlab中的stereo_triangulation方法进行三维可视化）


文件包括：
提取特征点：sift_opencv

以THU-MVS数据集为例的demo: demo

以h36m数据集为例的demo: h36m_demo

用matlab进行三界测距三维可视化：test_stereo_Triangulation

matlab进行三维重建过程中用的一些指令: yDailyFile

