# dog_breeds_classifier_CNN

The dog breed classifier is implemeted as a project for [Udacity Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree--nd101) using PyTorch library. Generaly, the classifier identifiys an estimate of the canine’s breed of a dog image. For more details, read [Udacity's original repo](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)

The overall flow consists of the following steps:

1. Import Datasets
2. Detect a human
3. Detect a dog
4. Create a CNN to Classify Dog Breeds (from Scratch)
5. Create a CNN to Classify Dog Breeds (using Transfer Learning)
6. Write your Algorithm
7. Test Your Algorithm

Detailed report is found in [the notebook](https://github.com/najwaWali/dog_breeds_classifier_CNN/blob/master/dog_app.ipynb).
feel free to use the notebook to improve or re-train the model.

### Dataset
- Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in this project's home directory, at the location `/dogImages`.
- Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the home diretcory, at location `/lfw`.

Note: make sure to put the correct path when you load the files. If you place them in the project's home directory, change the path name in the code before you load the data

```python
# load filenames for human and dog images
human_files = np.array(glob("lfw/*/*"))
dog_files = np.array(glob("dogImages/*/*/*"))
```

### Enviroment 

- Python 3.7+ 
- Jupyter Notebook 6.0.1+ 


