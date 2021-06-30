Sidewalk Data
===================
_TW-AI-Dataset-19009_

Description
-------------------
Dataset annotating 29 objects that are a hindrance to walking on sidewalks with Bounding Box and Polygon Segmentation.  
Dataset annotating sidewalks condition information with Polygon Segmentation and Masking.


Specification
-------------------
|Data size|670,000 images<br>(Bounding Box 350,000 / Polygon Segmentation 100,000 / Surface Masking 50,000 / Depth Prediction 170,000)|
|:---|:---|
|Depth Prediction config| Depth Prediction 1set = 8 images + 1 conf file 8 types of images <br>• Raw_Left , Raw_Right  <br>• Crop_Left , Crop_Right <br>•  Confidence , Confidence_save  <br>• Disparity , Disparity16|
|Collecting method|Crowd Sourcing, take a picture of spot|
|Device|Mobile phone (1920 * 1080 px)<br>ZED Stereo camera(1920 * 1080 px)|
|Data format|jpg (image) / png (mask image, depth image) / xml (annotation file) / conf (depth calibration file)|
|Data diversity|Region(seoul, daejeon, sejong, gimpo, goyang, busan)<br>Road(sidewalk, side road, crosswalk)<br>Weather(sunny, cloudy, rain)<br>Time(day, night)|

Examples
---------------
|Bounding Box| <img src="Sample Data\sidewalk_image1.png" width="450px"></img> |
|:---|:---|
|Polygon Segmentation| <img src="Sample Data\sidewalk_image2.png" width="450px"></img> |
|Surface Masking| <img src="Sample Data\sidewalk_image3.png" width="450px"></img><br><img src="Sample Data\sidewalk_image4.png" width="450px"></img> |
|Depth Prediction| <img src="Sample Data\sidewalk_image5.png" width="450px"></img><br><img src="Sample Data\sidewalk_image6.png" width="450px"></img> |

* Bounding Box 189 images and their annotation file  
* Polygon Segmentation 273 images and their annotation file  
* Surface Masking 119 images, 119 masking image and annotation file
* Depth Prediction 8 images and their calibration file|

License
---------------
* [License policy documentation](https://github.com/TestworksDataManagement/Sidewalk_Data/blob/main/TestWorks%20Dataset%20License.pdf) for the Testworks Dataset

Contact TestWorks
-----------------
* Tel : +82-2-423-5178
* E-mail : <cs@testworks.co.kr>
* Fax : +82-2-424-5178



