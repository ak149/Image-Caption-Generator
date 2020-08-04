# Image-Caption-Generator

A neural network to generate captions for an image using CNN and RNN with BEAM Search.

<p align="center">
  <strong>Examples</strong>
</p>

<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1600/1*6BFOIdSHlk24Z3DFEakvnQ.png" width="85%" title="Example of Image Captioning" alt="Example of Image Captioning">
</p>

<p align="center">
	Image Credits : <a href="https://towardsdatascience.com/image-captioning-in-deep-learning-9cd23fb4d8d2">Towardsdatascience</a>
</p>

#### Requirements

Recommended System Requirements to train model.

<ul type="square">
	<li>A good CPU and a GPU with atleast 8GB memory</li>
	<li>Atleast 8GB of RAM</li>
	<li>Active internet connection so that keras can download inceptionv3/vgg16 model weights</li>
</ul>

Required libraries for Python along with their version numbers used while making & testing of this project

<ul type="square">
	<li>Python - 3.6.7</li>
	<li>Numpy - 1.16.4</li>
	<li>Tensorflow - 1.13.1</li>
	<li>Keras - 2.2.4</li>
	<li>nltk - 3.2.5</li>
	<li>PIL - 4.3.0</li>
	<li>Matplotlib - 3.0.3</li>
	<li>tqdm - 4.28.1</li>
</ul>

<strong>Here are some direct download links:

<ul type="square">
	<li><a href="https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip">Flickr8k_Dataset</a></li>
	<li><a href="https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip">Flickr8k_text</a></li>
	Download Link Credits:<a href="https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/"> Jason Brownlee</a>
</ul>

###### Note: You can also build your model on online platforms like Google Colab or Kaggle or any other platforms if you do not have the required specifications, as I did.



#### Generated Captions on Test Images

<img width="50%" src="https://github.com/ak149/Image-Caption-Generator/blob/master/Outputs/output--1322323208_c7ecb742c6.jpg">
<img width="50%" src="https://github.com/ak149/Image-Caption-Generator/blob/master/Outputs/output--2677656448_6b7e7702af.jpg">


#### References

<ul type="square">
	<li><a href="https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Vinyals_Show_and_Tell_2015_CVPR_paper.pdf">Show and Tell: A Neural Image Caption Generator</a> - Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan</li>
	<li><a href="https://arxiv.org/abs/1703.09137">Where to put the Image in an Image Caption Generator</a> - Marc Tanti, Albert Gatt, Kenneth P. Camilleri</li>
	<li><a href="https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/">How to Develop a Deep Learning Photo Caption Generator from Scratch</a></li>
</ul>
