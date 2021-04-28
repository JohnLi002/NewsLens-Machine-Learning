# NewsLens

The overall purpose of NewsLens is to help highlight the bias present in articles. Currently this repository only contains files related to a machine learning algorithms with the purpose of predicting the news outlet based on the text given to it as well as various other files with the purpose of bringing our project to life. We are far from done however we hope that in the future we can complete it.

There are several csv files we used but are not present within this github. If you want to use the datasets we used, everything originates from the "All the News" in [Kaggle](https://www.kaggle.com/snapcrack/all-the-news). You can use our Categorize_Datasets.py and Create_Test_Dataset.py files within the Datasets folder to help create csv files that were used.

We have saved our current model in the h5 file model.h5.

## Files Created

### Keyword Extraction Algorithms
Files that start with “Datasets” are files that deal with keyword extraction. Each and every single one of them have a different keyword extraction method that was used.

### Neural Network
The files that start with “Neural_Network” are files that deal with the creation of a neural network. “Neural_Network_Test_Code” is the code that was used to create and save our neural network model. “Neural_Network_Load_Code” takes the saved model and loads it up so that it can be used to get predictions without having to go through the process of training.

### Naive Bayes
There is a single “Naive_Bayes_Code” is the file that deals with the creation of the naive bayes algorithm.

### Datasets
The two files, “Create_Test_Dataset_Code'' and “Categorize_Datasets_Code” both pertain to creating csv files from the “All the News” dataset that we used. The “Create_Test_Dataset_Code” creates a single large dataset to be used for training while the “Categorize_Datasets_Code” creates a separate dataset that only constrains content with the same publisher.


## Libraries were installed
If you are having trouble with using any of these libraries despite installing the necessary them, please try to use anaconda and create an environment that solely for the specific packages needed. That is what was had done to run some of these files. The following libraries mentioned are linked to their Github pages. Check their README.md for more information and links to their documentation as well as how to install their libraries. Some of these libraries have prerequisite but I only mentioned the ones below because they are the libraries that I have specified to be imported in some of the code. 

### Libraries used to create the Neural Network
[Sci-Kit Learn](https://github.com/scikit-learn/scikit-learn)

[TensorFlow](https://github.com/tensorflow/tensorflow/)

[TensorFlow-Hub](https://github.com/tensorflow/hub)
-Was used for Google's Universal Sentence Encoder

[Keras](https://github.com/keras-team/keras)
-For this project Keras was installed, and you can learn to do so [here](https://pypi.org/project/keras/) as the documentation within does not mention how to do so. However there seems to also be the option of using Keras by simply importing it through TensorFlow. You will need to modify some parts of the code if you choose to use Keras through TensorFlow.

### Libraries used to create the Naive Bayes algorithm
[Sci-Kit learn](https://github.com/scikit-learn/scikit-learn)

[nltk](https://github.com/nltk/nltk)

### Libraries used for Keyword Extraction
[Sci-Kit learn](https://github.com/scikit-learn/scikit-learn)
-For TF-IDF

[rake-nltk](https://github.com/csurfer/rake-nltk)

[gensim](https://github.com/RaRe-Technologies/gensim)
-For TextRank method

[YAKE](https://github.com/LIAAD/yake)

[KeyBERT](https://github.com/MaartenGr/KeyBERT)

### Libraries used to visual results of Neural Network and Naive Bayes Algorithms
[Seaborn](https://github.com/mwaskom/seaborn) *Seaborn also required the 3 libaries below*

[Numpy](https://github.com/numpy/numpy)

[Matlabplot](https://github.com/matplotlib/matplotlib)

[pandas](https://github.com/pandas-dev/pandas)