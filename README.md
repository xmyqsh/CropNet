# CropNet
Double boost APs without extra order of computation


Experience with RegNet800MF as backbone which is GPU friendly by minimizing the GPU unfriendly activation operation,
for fast experience on large waymo dataset.

16 FPS on a 800x1200 image with extreme small object in waymo open dataset.

Could be serve as a 100m+ object detector while providing semantic features for [FSN](https://github.com/xmyqsh/FSN) in the meaning while.

