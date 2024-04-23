# Multi-lingual-Indian-text-detector-for-mobile-devices

Detection of text present in natural scene images is a challenging problem owing to its significant variations in the appearance of the texts as well as the background. The task becomes even more difficult for Indian texts, due to the presence of multiple languages and scripts. Most of the recent efficient schemes use very deep CNN which requires large memory and computation. In this paper, we proposed a multi-lingual text detection system based on the compressed versions of an object detection framework called YOLO (You Only Look Once) namely, YOLO v3-Tiny and YOLO v4-Tiny. The aspect ratios of the anchor boxes are calculated using K-means clustering on the ground truth values, so that it can accurately detect words of varying lengths. The text detector has been evaluated on the IndicSceneText2017 data set which consists of three Indian languages along with English. Experimental results prove the efficiency of the proposed scheme, for use in embedded systems and mobile devices due to its fast inference speed and small model size.

The repository includes the code and the **labeling tool** used for labeling the image data in **YOLO Darknet** and **Pascal-VOC** format.

### Please cite the repository if you find it useful :



@inproceedings{naosekpam2020multi, <br />
  title={Multi-lingual Indian text detector for mobile devices},<br />
  author={Naosekpam, Veronica and Kumar, Naukesh and Sahu, Nilkanta},<br />
  booktitle={International Conference on Computer Vision and Image Processing},<br />
  pages={243--254},<br />
  year={2020},<br />
  organization={Springer}<br />
}

or 

Naosekpam, Veronica, Naukesh Kumar, and Nilkanta Sahu. "Multi-lingual Indian text detector for mobile devices." International Conference on Computer Vision and Image Processing. Springer, Singapore, 2020.
