# image_caption_bot
### It's a Keras model for generating text on images deployed on a flask server<br/>
## Made as a project under coding blocks machine learning course(2020).<br/>
<br/>
## The model was train on Flickr-8k dataset available on kaggle(https://www.kaggle.com/shadabhussain/flickr8k)</br>
## Final model uses Resnet-50(trained on imagenet dataset) as convolutional base and glove6B-50d(developed by stanford) embedding as embedding matrix in LSTM layers.<br/>
### app.py contains python code to deploy model on flask-server model_script.py contains structure of model and function to preprocess images to generate Captions
