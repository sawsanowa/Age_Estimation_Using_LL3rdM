
<h3>This project consists of multiple parts</h3>

- [x] Part1: Applying image segmentation and extraction of the lower left third molar using the U-Net architecture.
- [x] Part2: Third molar measurements. 
- [x] Part3: Age estimation using machine learning algorithms.

<hr>

<p>
 
 <h3>A demo apps are Available on the following Hugging Face spaces!</h3>
 
 -	[Lower Left Third Molar segmentation and extraction](https://huggingface.co/spaces/AlowaSawsan/Third-Molar-Segmentation)
 -	[Lower Left Third Molar measurements](https://huggingface.co/spaces/AlowaSawsan/Lower-Left-Third-Molar-Detection-and-Measurements)
 
 </p>
 
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

<h3> Tools </h3>

<p>
 
-	[TensorFlow](https://www.tensorflow.org/resources/libraries-extensions) - an ecosystem that provides many libraries used to develop and train models using multiple languages including python. 
- [Skimage](https://scikit-image.org/docs/stable/api/skimage.html) - a package from scikit-image contains a collection of algorithms used for image processing. Mostly we will use utilities from the subpackage io and transform. io subpackage is used for reading, displaying, and saving images. Some of these utilities imread, imshow, and resize. Imread is used for loading images while imshow is used for displaying the images. From the subpackage transform, the utility resize allows to up-size or down-size N-dimensional images to match specific sizes.
- [cv2](https://pypi.org/project/opencv-python/) – A python computer vision library used to read, modify, and transform images into various formats. 
- [Imutils](https://pypi.org/project/imutils/)  – A package contains image processing functions. From Imutils, we will import the “perspective” function, which is used to sort the points based on their coordinates. 
- [SciPy](https://scipy.github.io/devdocs/index.html)  – A collection of convenience functions and mathematical algorithms. From SciPy, we will import the subpackage “spatial” that contains the function “distance,” which is used to measure the distance between points. 
- [Matplotlib](https://matplotlib.org/)  – A python library for creating visualizations. 
- [NumPy](https://numpy.org/)  – A python package used for scientific computing with python. Images in python are represented as NumPy arrays. 

</p>

<h3> Algorithms </h3>

<p>
 - [k-nearest neighbors](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
 - [Decision Tree](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
 - [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
 - [RandomForest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
 - [Gradient Boosting](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)
 - [Latent Dirichlet Allocation](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.LatentDirichletAllocation.html)
 - [Support Vector Machine](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
 - [Multi-layer Perceptron](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html)
</p>
