# COSC2753 - Machine Learning Assignment 2 - 2024 A

## Group number: SG_T3_G1

## Contributors

|       Name       |    Id    | contributions |
| :--------------: | :------: | :-----------: |
|   Hur HyeonBin   | s3740878 |      25%      |
|  Khang Lu Minh   | s3863969 |      25%      |
| Khanh Trinh Xuan | s3927152 |      25%      |
| Khoi Hoang Minh  | s3854233 |      0%       |
|  Tuan Vo Hoang   | s3868189 |      25%      |

## Set up

> conda install numpy

> conda install pandas

> conda install matplotlib

> conda install seaborn

> conda install -c conda-forge opencv # For OpenCV

> conda install -c conda-forge tensorflow

> conda install -c conda-forge keras

> conda install scikit-learn

> conda install -c conda-forge pillow # For PIL

> conda install -c conda-forge tqdm

### libraries

-   Numpy - A library for numerical computations.
-   Pandas - Provides data structures and tools for data manipulation and analysis.
-   Matplotlib - Used for creating static, interactive, and animated visualizations in Python.
-   Seaborn - A library based on matplotlib for making statistical graphics.
-   OpenCV (cv2) - A library for image processing and computer vision tasks.
-   TensorFlow - A comprehensive library for machine learning and deep learning.
-   Keras - A high-level neural networks API running on top of TensorFlow.
-   Scikit-Learn - A library that provides simple and efficient tools for data mining and data analysis.
-   PIL (from PIL.Image) - Used for opening, manipulating, and saving many different image file formats.
-   tqdm - A tool for showing progress bars during loops.
-   glob - Provides a means for Python to retrieve files/pathnames matching a specified pattern.
-   shutil - Offers high-level operations on files and collections of files.
-   os - Provides a way of using operating system dependent functionality.
-   random - Implements pseudo-random number generators for various distributions.
-   pickle - Implements binary protocols for serializing and de-serializing a - - Python object structure.
-   concurrent.futures - Provides a high-level interface for asynchronously executing callables.

## Known mistakes

### Task 1

The result of the cross-validation with a batch size of 32 and learning rate was accidentally lost during version management, but we saved the results as a text file, so the model's result is displayed with text.

The result of the 0.5 dropout rate accidentally disappeared during version management, but we saved the result as a text file, so it is shown in the text.

### Task 2

Task 2 model was trained under a smaller dataset instead of the whole dataset. 

### Task 3

Task 3 used pre-tranied model EfficientNetB0 and Nereest Neighbor to execute the task. 

## How to run Task 3

