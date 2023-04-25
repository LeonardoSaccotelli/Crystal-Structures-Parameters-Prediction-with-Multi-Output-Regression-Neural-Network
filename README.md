# Crystal-Structures-Parameters-Prediction-with-Multi-Output-Regression-Neural-Network
Preliminary investigation of machine learning techniques to perform parameters estimation for different crystal structure: <b>hexagonal, monoclinic, orthorhombic, tetragonal, triclinic, trigonal</b>.
Starting from a spectral, which represent a crystal structure, the aim is to develop a ML model which can predict the three different parameters size: <i>a</i>, <i>b</i>, <i>c</i>.
Each observation is a couple (x<sub>i</sub>, y<sub>i</sub>), for which x<sub>i</sub> is a value between 0 and 90, with an increment of 0.02; y<sub>i</sub> is the intensity. 
<br>For each structure the three dimensions are not all equal; thus, is a multi-output regression problem. A Multi-Output Neural Network has been implemented for each crystal structure.
## Project workflow
* <b>Task 1: Data Preparation</b>

* <b>Task 2: Data Analysis Overview</b>
  * Descriptive Statistics
  * Boxplot
  * Correlation Matrix
  * Pairplot

* <b>Tack 3: Multi-Output Regression



