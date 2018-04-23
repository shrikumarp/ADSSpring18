# ADSSpring18
Final Project Code for INFO7390 ADS 

Yelp sentiment Analysis and Text Classification.
We perform pre-processing and analysis of the restaurant or food establishment review texts and their corresponding star ratings  from yelp. We use various Machine learning algorithms for text classification and also use Bidirectional LSTM neural network and compare and analyze the accuracy and results of these classifiers. Finally, we build a simple recommender system which uses concept of item based collaborative Filtering, which suggests restaurants or food establishment to a user based on the correlation of the similar restaurants based on the ratings given by the user to the restaurants rated by that user.

Please make sure you have the following libraries installed before continuing running this notebook. We use Tensorflow,(CPU only), Keras and Scikit-Learn.
pip install tensorflow
#keras needs tensorflow or other backends as caffe or theano
pip install keras
Pip install sklearn

Download the Glove text word vector file here: https://www.dropbox.com/s/my83b23ev2h9qgp/glove.6B.50d.txt?dl=1 .After downloading please place it in the directory same as that of this notebook or give appropriate path while referencing the name of the text file in the code.
