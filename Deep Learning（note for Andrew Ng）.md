1. Neural Networks and Deep Learning 
2. Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization
3. Structing your Machine Learning project 
4. Convolutional Neural Networks
5. Natural Language Processing: Building sequence models



# What is a Neural Network

ReLu function : Rectified Linerar Unit -- Housing Price Prediction

input layer --> density connected neural --> outputs

Every input feature is connected to everyone.

given enough training examples with both x and y neural networks can figure out functions that accurately map from x to y.

It's useful in supervised learning incentives.  



# Deep Learning in Sepervised Learning



one type of machine learning  - lucrative 

online advertising     standard NN

photo tagging            CNN

speech recognition   RNN

machine translation  RNN

Autonomous driving  custom/complex/hybrid NN architecture





Standard NN Convolutional NN Recurrent NN 

Structured Data : in database

each of the features has a very well defined meaning 

Unstructured Data : audio image text etc

Speech recognition image recognition natural language processing on text 



the course will focus on structured data.



deeplearning.ai

forward pause/forward propagation step 

backward pause/backward propagation step

 

## Basics of Neural Network Programming 

## Binary Classification(二元分类)

3 64 * 64 matrices denote a picture in computer turn these pixel intensity values into a feature vector 

In binary classification, our goal is to learn a classifier that can input an image represented by this feature vector x. and predict whether the corresponding label y is 1 or 0.

that is whether this is a cat image or a non-cat image.

### Notation

A single training example is represented by a pair  (x,y) where x is an x-dimensional feature vector y is the label is either 0 or 1.

Your training sets will comprise m training examples

m : (x1,y1),(x2,y2)....  

### Logistic Regression

Linear regression / logistic regression

sigmoid function make the value of y be 0 - 1

keep the parameter W and parameter B separate 

### Logistic Regression cost function

![Screenshot 2022-12-08 at 21.48.34](/Users/yangwenbo/Desktop/DeepLearning/images/Screenshot%202022-12-08%20at%2021.48.34.png)

Loss(error) function: to measure how well our algorithm is doing 

how good our output y hat is when the true label is y.

![Screenshot 2022-12-08 at 21.58.00](/Users/yangwenbo/Desktop/DeepLearning/images/Screenshot%202022-12-08%20at%2021.58.00.png)



Coss function: which measures how well you are doing an entire training set

the loss function is applied to just a single training example , the cost function is the cost of your parameters

### Gradient Descent

![Screenshot 2022-12-11 at 15.06.05](/Users/yangwenbo/Desktop/DeepLearning/images/Screenshot%202022-12-11%20at%2015.06.05.png)

Derivative term





#### Gradient  descent on m examples

### Logistic regression on m examples













