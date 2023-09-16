# LiDARNet_ver2
This dataset is collected by an HDL-32E Velodyne LiDAR sensor carried by our UGV platform. Raw point clouds collected from a real outdoor scene are segmented into individual obstacles according to a fast spatial clustering method. We developed a semi-automatic 3D object labeling tool to store individual object point clouds. The UGV and a semi-automatic 3D object labeling tool are presented in the following figure.

<img src="image/Car.jpg" width="700" height="450">

<img src="image/Tool3.PNG" width="700" height="400">

We collected 1601 obstacles from several thousands of scanning frames, containing 6 kinds of common types. All the point coordinates are stored in .csv files with their original and after-centralized x, y, z coordinates.

<img src="image/object.PNG" width="700" height="700">


<br> 
<br> 

## LiDAR:
 ### **Train&Testing sample statistic**
|          | **pole** | **pedestrian** | **tree** | **bush** | **building** | **vehicle** |
| :---:    | :---:    |:---:           |:---:     |:---:     |:---:         |:---:        |
| Train    | 160      | 92             | 286      | 141      | 252          | 115         |
| Test     | 76       | 60             | 129      |    82    | 133          | 75          | 
| Total    | 236      | 152            | 415      | 223      | 385          | 190         |

<br> 
<br> 
  
## Citation
### **If you find our work useful in your research, please consider citing:**
 1.	Wei Song, Zhen Liu, Ying Guo, Su Sun, Guidong Zu, and Maozhen Li, DGPolarNet: Dynamic Graph Convolution Network for LiDAR Point Cloud Semantic Segmentation on Polar BEV, Remote Sensing, Vol.14, No.13: 3825. 2022, https://doi.org/10.3390/rs14153825
 2.	Wei Song, Dechao Li, Su Sun, Lingfeng Zhang, Yu Xin, Yunsick Sung, and Ryong Choi, 2D&3DHNet for 3D Object Classification in LiDAR Point Cloud, Remote Sensing, Vol.14, No.13: 3146. 2022, https://doi.org/10.3390/rs14133146

<br> 
<br> 

## Principal Investigator
Wei Song (sw@ncut.edu.cn)
<br> 
<br> 
  

