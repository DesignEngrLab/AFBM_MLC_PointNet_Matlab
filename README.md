Research code used to generate results for ASME IDETC Paper 138095 (Zachariah A. Connor, Shital Sable, Matthew I. Campbell, and Rob B. Stone), published August 2024. Please cite this paper properly when using this code for research purposes. Citation details forthcoming.

You must download the point clouds to run this code here: (https://drive.google.com/drive/folders/1dfZN_-reJt7TtgVvL5hnfulKqrutaJ8R?usp=drive_link)
It is a 9 GB download, but once it is unzipped it is approximately 12 GB. 

This code only works on R2023b or later. It will NOT work on R2023a or earlier versions of MATLAB. 
This code was tested on a Windows 11 Pro desktop with an Intel i5 12600k, 32GB of DDR4 RAM, and an Nvidia RTX 3060 with 12GB of VRAM.

Files:

-MLC_PointNetAFBM.mlx: Code for MLC-PointNet, data preprocessing, training, and testing.
-AFBMData_NoChairs.csv: File containing the point clouds and Functional Basis labels used.
-Various .ply files: Example point clouds to test code on.
-fold_#.csv: files containing pre-partitioned point cloud files. 
