# floor_detection
Main code  is run on the online colab platform.
Comments are given on the each steps of the code.
floor_detection.ipynb: Is the main code file.
shoe_pc.ply: Is the input file.
output_images: Contains the snapshots of the outputs. floor.png is for floor detection, pointcloud_before rotation.png showing the point cloud before rotation, pointcloud_after rotation.png showing the point cloud after rotation, final_mesh.png is the output for mesh constructed on the pointcloud after rotation.
output_ply_files: Output ply files at different steps. For visualization meshlab has been used. floor.ply contains output for floor detection which shown in red colour, object.ply for the shoe in blue color, floor_rotate.ply and object_rotate,ply for after aplying necessary rotation,and floor_mesh.ply and object_mesh.ply after creating the traingular meshes from the rotated point cloud.


