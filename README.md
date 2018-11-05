# Saliency-Map-Implementation-in-Vide-Codec-HM
In HM 16.12, the saliency detection method proposed in [2] is implemented，where the saliency-based optimization can be adopted in video coding. 

Added source files:
在TLibEncoder工程下添加：
GMRsaliency.h
GMRsaliency.cpp
SLIC.h
SLIC.cpp


OpenCV3.0+VS2013 环境配置：

VC++ 目录：
包含目录：将Opencv的include文件路径包含进去:..build\include, ..\build\include\opencv, ..\build\include\opencv2
库目录：..build\x86\vc12\lib

连接器：
输入：将目录..build\x86\vc12\lib 下的所有.lib文件添加入附加依赖项


References:

[1] https://hevc.hhi.fraunhofer.de/trac/hevc/browser/tags
[2] Chuan Yang, Lihe Zhang, Huchuan Lu, Ruan Xiang, and Ming Hsuan Yang, “Saliency detection via graph-based manifold ranking,” in IEEE Conference on Computer Vision and Pattern Recognition, 2013, pp. 3166–3173.
[3] https://github.com/yangchuancv/ranking_saliency
