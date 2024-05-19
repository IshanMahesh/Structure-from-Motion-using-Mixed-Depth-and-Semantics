# Structure-from-Motion-using-Mixed-Depth-and-Semantics
ENPM673


Required Libraries/Frameworks/tools

    1) cv2
    2) torch
    3) matplotlib
    4) timm
    5) numpy
    6) os
    7) sklearn
    8) tdqm
    9) meshlab
    10) cuda (optional)


A) For generating front perspective point cloud using MIDAS
1) Run the file PointCloudMIDAS.py (midas should be automatically installed)
2) A .ply file named point_cloud_MIDAS will be generated
3) Open that .ply file in MeshLab for visualization.

B) For generating point cloud of statueimages using MIDAS
1) In the 360PointCloudMIDAS.py file change the dataset_folder location according to your requirement and run the code.
2) A .ply file named point_cloud_360_MIDAS will be generated(code takes a while to run according to your device specs)
3) Open that .ply file in MeshLab for visualization.

C) For generating point cloud using COLMAP
1) Copy colmap folder and run COLMAP.bat.
2) Select the reconstruction tab, then select workspace and image dataset folder.
3) Tick the dense option and select poisson and just run.
4) Variety of folders associated with colmap will be generated in your workspace as well, which you can ignore if you want. 
