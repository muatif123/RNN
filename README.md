# Recurrent Neutal Network using Tensorflow and Keras
Recurrent Neural Network(RNN) are a type of Neural Network where the output from previous step are fed as input to the current step. In traditional neural networks, all the inputs and outputs are independent of each other, but in cases like when it is required to predict the next word of a sentence, the previous words are required and hence there is a need to remember the previous words. Thus RNN came into existence, which solved this issue with the help of a Hidden Layer. The main and most important feature of RNN is Hidden state, which remembers some information about a sequence.

Refer: https://www.geeksforgeeks.org/introduction-to-recurrent-neural-network/ for full understanding of neural network

## About Tensorflow

TensorFlow is an end-to-end open source platform for machine learning
TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML, and gives developers the ability to easily build and deploy ML-powered applications.

TensorFlow provides a collection of workflows with intuitive, high-level APIs for both beginners and experts to create machine learning models in numerous languages. Developers have the option to deploy models on a number of platforms such as on servers, in the cloud, on mobile and edge devices, in browsers, and on many other JavaScript platforms. This enables developers to go from model building and training to deployment much more easily.

Easy model building
Build and train ML models easily using intuitive high-level APIs like Keras with eager execution, which makes for immediate model iteration and easy debugging.

Robust ML production anywhere
Easily train and deploy models in the cloud, on-prem, in the browser, or on-device no matter what language you use.

Powerful experimentation for research
A simple and flexible architecture to take new ideas from concept to code, to state-of-the-art models, and to publication faster.

Refer: https://opensource.google/projects/tensorflow 

## About Keras

Keras is an open source deep learning framework for python. It has been developed by an artificial intelligence researcher at Google named Francois Chollet. Leading organizations like Google, Square, Netflix, Huawei and Uber are currently using Keras. This tutorial walks through the installation of Keras, basics of deep learning, Keras models, Keras layers, Keras modules and finally conclude with some real-time applications.
More on Keras : https://www.tutorialspoint.com/keras/index.htm


### About the uploaded files
Contains 3 Jupyter Notebook files which explain the working of RNN with tensorflow and keras on different datasets

1. ##### RNN SineWave : Understand the working of RNN with this simple sinewave created using np.random data points and predicting further sinewave using tensorflow and keras.
2. ##### RNN TimeSeries: Understand of time difference in sales of an organization and predicting the future sales of timeseries with the help of historic data using tensorflow, keras and lstm model.
3. ##### RNN Multivariate: This is the energy storing time based dataset, which stores the energy data every 10 minutes for the last 4 months. With the help of TimeSeriesGenerator and LSTM model, we can predict the output sinewave of the energy.
<br>
<br>

For better understanding of sequential model : https://keras.io/guides/sequential_model/
For better understanding of lstm model : https://www.tutorialspoint.com/time_series/time_series_lstm_model.htm#:~:text=It%20is%20special%20kind%20of,layers%20interacting%20with%20each%20other
For better understanding of timeseriesgenerator : https://medium.com/swlh/timeseriesgenerator-a-deep-down-with-example-in-python-dfe32dcb2a24   
