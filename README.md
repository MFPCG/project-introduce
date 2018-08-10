# 项目介绍

这是一个多摄像头全景照相机项目，包含硬件端、网页端及移动端。各端主要实现功能如下：

[硬件端](https://github.com/MFPCG/panorama-stitching)：基于开源硬件平台RK3399，驱动三个鱼眼镜头进行拍照，并将拍摄得到的鱼眼图像进行合成，得到一张比例为2:1的全景图，分别传输至移动端和网页端进行展示。

[移动端](https://github.com/MFPCG/panorama-camera-client)：对硬件端进行拍照控制及全景图像的展示。

[网页端](https://github.com/MFPCG/web-panorama-display)：对全景图像进行展示。

### 实物图

整体实物图：

<img src="https://github.com/MFPCG/project-introduce/blob/master/Images/%E5%85%A8%E6%99%AF%E7%9B%B8%E6%9C%BA%E5%AE%9E%E7%89%A9%E5%9B%BE.jpg" height="600" width="400">

鱼眼镜头：

<img src="https://github.com/MFPCG/project-introduce/blob/master/Images/%E9%B1%BC%E7%9C%BC%E9%95%9C%E5%A4%B4.png">