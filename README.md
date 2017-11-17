three.js companion to implement a drop and drag reader and model parser.

All data are converted to a local coordinate system. 

Input files are csv 4 column XYZG.
voxel.html loads a regularly spaced solid model. To speed the WebGL experience, a hollowing out algorithm is used to only render the voxels on the outside of the solid. 

LiDAR.html displays large point cloud datasets. 

4View.html shows a solid model (simlarly to voxel) but with 4 simultaneous views. 