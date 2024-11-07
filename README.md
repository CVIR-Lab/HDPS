# HDPS
The repository contains the code and dataset in HDPS paradigm, which is currently being submitted to Nature Machine Intelligence.
The code is coming soon!
we proposed a new paradigm in deep learning, High-Dimensional Projection Selection(HDPS), which is applicable to most network architectures. HDPS integrates the relationship between the target manifold and the input manifold, merging their information interactions to construct a high-dimensional manifold. The foundational step in constructing this high-dimensional manifold lies in identifying the most fundamental properties inherent to the target domain. With that, we then seek to establish a connection between the source manifold and the target manifold, where we finally got a high-dimensional manifold. Through this high-dimensional manifold space, we establish a more effective mapping between the probability distributions of the given target and the input data. Notably, the proposed paradigm introduces several additional nodes to the traditional end-to-end neural network structure, which alleviates two key issues that have long constrained research in computer vision and computational imaging: the challenge of fitting complex distributions with limited samples and the unavoidable information-loosing in initial values.
## Performance on NLOS datasets
In the images we present, (a) is the input and (b) is the target. (c) and (d) show the reconstruction results from HDPS, where (c) represents f(z) and (d) represents f(f(z)).
### NLOS-MNIST
![image](https://github.com/CVIR-Lab/HDPS/blob/main/image/web_mnist.png)

### NLOS-passive
![image](https://github.com/CVIR-Lab/HDPS/blob/main/image/web_gray.png)
The figure shows the performance on NLOS scene with reconstructing model-face in gray image.
![image](https://github.com/CVIR-Lab/HDPS/blob/main/image/web_rgb.png)
The figure shows the performance on NLOS scene with reconstructing model-face in RGB image.

## Performance on Low Light Image Enhancement
Here we present some video-result on sdsd datasets.
### sdsd-indoor
<img src="https://github.com/CVIR-Lab/HDPS/blob/main/image/sdsdin_low_output.gif" width="240" height="120"><img src="https://github.com/CVIR-Lab/HDPS/blob/main/image/sdsdin_gt_output.gif" width="240" height="120"><img src="https://github.com/CVIR-Lab/HDPS/blob/main/image/sdsdin_hdps_output.gif" width="240" height="120">
We reorganized the dataset page, please see the new official dataset  [**NLOS**](https://github.com/CVIR-Lab/NLOS) of HDPS for detail.
