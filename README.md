# LiDARNet_ver2
This dataset is collected by an HDL-32E Velodyne LiDAR sensor carried by our UGV platform. Raw point clouds collected from a real outdoor scene are segmented into individual obstacles according to a fast spatial clustering method [1]. We developed a semi-automatic 3D object labeling tool to store individual object point clouds [2]. The UGV and a semi-automatic 3D object labeling tool are presented in the following figure.

<img src="image/Car.jpg" width="700" height="450">

<img src="image/Tool3.PNG" width="700" height="400">

We collected 1601 obstacles from several thousands of scanning frames, containing 6 kinds of common types. All the point coordinates are stored in .csv files with their original and after-centralized x, y, z coordinates.

<img src="image/object.PNG" width="700" height="700">

# LiDAR:

 **Train&Testing sample statistic**
|          | **pole** | **pedestrian** | **tree** | **bush** | **building** | **vehicle** |
| :---:    | :---:    |:---:           |:---:     |:---:     |:---:         |:---:        |
| Train    | 160      | 92             | 286      | 141      | 252          | 115         |
| Test     | 76       | 60             | 129      |    82    | 133          | 75          | 
| Total    | 236      | 152            | 415      | 223      | 385          | 190         |

# Citation
**If you find our work useful in your research, please consider citing:**
  1. Y Tian, W Song, L Chen, et al., A Fast Spatial Clustering Method for Sparse LiDAR Point Clouds Using GPU Programming, Sensors 20 (8), 2309
  2. W Song, L Zhang, Y Tian, et al., CNN-based 3D object classification using Hough space of LiDAR point clouds, Human-centric Computing and Information Sciences 10 (1), 1-14
 
# Principal Investigator

Song Wei (sw@ncut.edu.cn); Tian Yifei (yb87403@um.edu.mo, tianyifei0000@sina.com)

# Project Researchers
Zhang Lifeng; Liu Zishu
