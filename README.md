DLO_3d
Deformable Linear Object Perception in 3D

Here is our [datasets download link (Google Drive)](https://drive.google.com/drive/folders/1KN0QBC6FsmyhhklCE6nIn7P7qk3VhoM_?usp=sharing).

In the .zip file, there are three files, train.zip and test.zip are used for DLO shape recovery training, and real_world_dataset.zip is used for real-world evaluation. In train.zip and test.zip, DLOs have the pixel value=120 and the background has the pixel value=60. On average 10 training images share the same test image, according to training images' suffix indicating their index. In real_world_dataset.zip, there are three subfolders, RGB, DEPTH, MASK. As their names show, RGB contains rgb images of 12 datasets, among them ten are wire_aug, one is wire, and one is transparent tubes. The same applies to DEPTH and MASK. Need to notice that, there is no ground-truth for the depth maps of deformable linear objects. Due to the limit of depth sensors, we cannot capture full depth maps of DLOs especially when there are occlusions. So far the depth maps in wire_aug are of best quality to show the depth information of DLOs, however, with less complex configurations. 

Simulation codes and shape recovery training codes will release according to the acceptence of our paper.