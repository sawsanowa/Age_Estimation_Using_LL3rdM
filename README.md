
<h3>This project consists of multiple parts</h3>

- [x] Part1: Applying image segmentation for the lower left third molar using the U-Net architecture.
- [x] Part2: Third molar measurements. 
- [ ] Part3: Age estimation using machine learning algorithms.

<hr>

<h3>Lower Left Third Molar (LL3rdM) Detection</h3>
Three models are evaluated:

- U-net
- Attention U-net
- U-net++
 
<hr>

<h3>Proposed U-net Model Architecture</h3>

<p align="center"> 

<img width="700" height="400" src="https://github.com/sawsanowa/Age_Estimation_Using_LL3rdM/blob/main/Model_Architecture/U-net%20Arch%20256x512x1.png"/>
 
</p>

<hr>

<h3>Segmentation Results </h3>


<p align="center"> 
 
 <img width="600" height="500" src="https://github.com/sawsanowa/Age_Estimation_Using_LL3rdM/blob/main/Figures/U-net_comparison.PNG"/>
 
</p>

<hr>

<h3> TOOLS AND ALGORITHMS </h3>

<p>
 
- [cv2](https://pypi.org/project/opencv-python/) – A python computer vision library used to read, modify, and transform images into various formats. 
- [Imutils](https://pypi.org/project/imutils/)  – A package contains image processing functions. From Imutils, we will import the “perspective” function, which is used to sort the points based on their coordinates. 
- [SciPy](https://scipy.github.io/devdocs/index.html)  – A collection of convenience functions and mathematical algorithms. From SciPy, we will import the subpackage “spatial” that contains the function “distance,” which is used to measure the distance between points. 
- [Matplotlib](https://matplotlib.org/)  – A python library for creating visualizations. 
- [NumPy](https://numpy.org/)  – A python package used for scientific computing with python. Images in python are represented as NumPy arrays. 

</p>
