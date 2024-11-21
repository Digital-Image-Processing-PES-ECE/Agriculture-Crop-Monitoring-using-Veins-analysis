# Project Name
AGRICULTURE CROP MONITORING  USING VEINS ANALYSIS

### Project Description:
 This project presents a dual-method approach for an analyzing leaf health by detecting abnormal vein widths and segmenting diseased areas using HSV-based color segmentation. The vein analysis identifies irregular structures and color segmentation highlights unhealthy regions. This approach aims to detect early pest detection precisily.
#### Summary - 
This project we use vein analysis and HSV - based segmentation to automate pest 
damage detection. Vein irregularities often indicate early plant stress, while colour-based 
segmentation effectively identifies diseased regions. Together, these methods provide a 
comprehensive solution for assessing leaf health and aiding precision agriculture. 

#### Course concepts used - 
1.image processing -greyscale conversion,image enhancment to enhance contrast usingg adaptive histogram equalization
2.  Morphological Operations: morphological operations to thicken the vein structure and dillation
3. -Edge detetction: for veins analysis
4.skeletonization:to precise vein width
   
#### Additional concepts used -
1. -hsv:Highlight diseased areas on the original image
2. - regionprops:inbuilt function to find connected components in the vein structure  by measuring area and perimeter
   
#### Dataset - 
https://www.kaggle.com/datasets/nirmalsankalana/crop-pest-and-disease-detection

#### Novelty - 
1. -uniquely combines vein structure irregularities or color-based segmentation to enhance detection accuracy. 
2. -The vein analysis identifies structural abnormalities which helps giving,indicative of 
pest-induced stress, while HSV segmentation highlights visual discoloration caused 
by disease or pests.
3.The use of skeletonization and distance transforms allows precise vein width measurement.
### Contributors:
1. Anushka keshri (pes1ug22ec042)
2. Spoorthi N(pes1ug22ec811)
### Outputs:
*  intermediate steps-conversion to greyscale image
*  edge detection to extract veins
*  dilution for analysing the veins
*  skeletonization
*  highlighting abnormal width based on thinning or thickening of leaf
*  highlighting abnormal region
* 

### References:
1. A. Soni, J. K. Soni and S. Hota, "Detection of Multiple Crop Diseases using Image Processing Techniques," 2021 IEEE High Performance Extreme Computing Conference (HPEC), Waltham, MA, USA, 2021, pp. 1-6, doi: 10.1109/HPEC49654.2021.9622812.

2.Z. Wang, C. Zhao, H. Zhang and H. Fan, "Real-Time Remote Monitoring and Warning System in General Agriculture Environment," 2011 International Conference of Information Technology, Computer Engineering and Management Sciences, Nanjing, China, 2011, pp. 160-163, doi: 10.1109/ICM.2011.228. 
3.Q. Huang, W. Wu, L. Zhang and D. Li, "MODIS-NDVI-Based crop growth monitoring in China Agriculture Remote Sensing Monitoring System," 2010 Second IITA International Conference on Geoscience and Remote Sensing, Qingdao, China, 2010, pp. 287-290, doi: 10.1109/IITA-GRS.2010.5603948. 
### Limitations:
1.only analyzing leaf with white background doesnt work if background is coloured
2.did not tried taking image from camera till now it is working well with image provided by dataset
# Future Work:
1.to combine both method together and get  precise output 
2.informing the farmer how much it is prone to disease and also  concentration of NPK to be used precisialy  to remove that pest

