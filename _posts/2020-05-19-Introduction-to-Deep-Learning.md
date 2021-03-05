---
title: Introduction to Deep Learning
author: Ankit
color: red
tags: DL AI
layout: post
date: 19-05-2020
---
Okay so, Hello Guys, Wassup!  

Now a days, more than ever, the word **Deep Learning** has caught everyone's attention in the Software Community. It has become somewhat of a buzzword, so does everyone says. But, to be honest, not everyone understands what it is. Just catching someone's eye with big words might 
have been a trend in past, but no more now. So, in order to have a clear and better understanding of Deep Learning, I’ll be demystifying the buzzword that is deep learning, and will provide an intuition of how it works.  

### What is Deep Learning?  

Well casually speaking, like all other Machine Learning methods, deep learning is a method that takes in an input X, and uses it to predict an output of Y. What makes it different from machine learning is that while doing so, it uses a so called 'neuron' to perform all the computations involved. This prediction can be in the form of inference from classification scenarios (don't worry, we'll discuss it later) or it may take form of a full-fledged prediction of Stock Prices, or maybe Weather, or any other thing that **has a pattern involved**. It isn't necessary that this pattern might be visible to you in its simplest form, for eg. while plotting a point on a curve, the equation of the curve provides a clear cut pattern but on the otherhand if you want to infer whether a given image is Cat or Dog, What will you do?  


There is nothing like a linear or quadratic equation which you might utilize to get even close to the solution. In such a case, the characteristics of cats and dogs, which obviously are different, serve as the parameter to identify them. These characteristics are termed as **features**.  

In other words, it might be difficult for you to find the pattern I described above, but not necessarily for a computer. What deep learning models do is given a large dataset of input and output pairs, a deep learning algorithm will be employed that will try to minimize the difference between its prediction and expected output. By doing this, it tries to learn the association/pattern between given inputs and outputs — this in turn allows a deep learning model to generalize to inputs that it hasn’t seen before. And hence, after 'teaching' our model, we can expect it to make decisions on its own whenever a new example will be provided.  

<!-- Image   -->  

As an example, let’s say that inputs are images of dogs and cats, and outputs are labels for those images (i.e. is the input picture is a dog or a cat). If an input has a label of a dog, then the deep learning algorithm will predict a dog. What will happen is that the features of my given image (e.g. sharp teeth, facial features) will be recognized as the ones being associated with a dog by the Neural Network and hence, the result.  

### A Formal Introduction

Deep Learning is a subfield of machine learning concerned with algorithms inspired by the structure and function of the brain called artificial neural networks. Now Artificial Neural Networks(or ANN's) might sound a bit new to some of you, for  that I'll 
describe ANN's in another post. For now, just have a basic idea of them.  

#### Artificial Neural Networks  
**Artificial neural networks**, like the human body's biological neural network, have a layered architecture and each network node (connection point) has the capability to process input and forward output to other nodes in the network. In both artificial and biological architectures, the nodes are called neurons and the connections are characterized by synaptic weights, which represent the significance of the connection. As new data is received and processed, the synaptic weights change and this is how learning occurs.  

In both artificial and biological networks, when neurons process the input they receive, they decide whether the output should be passed on to the next layer as input. The decision of whether or not to send information on is called bias and it’s determined by an activation function built into the system. For example, an artificial neuron may only pass an output signal on to the next layer if its inputs (which are actually voltages) sum to a value above some particular threshold value. Because activation functions can either be linear or non-linear, neurons will often have a wide range of convergence and divergence. Divergence is the ability for one neuron to communicate with many other neurons in the network and convergence is the ability for one neuron to receive input from many other neurons in the network.

### Syntax Highlighting

```python
# Trial for python
t = int(input())
for _ in range(t):
  print(_)
```
```cpp
//  Trial for cpp
#include <iostream>
using namespace std;
cout >> "Hello World.!";
```
```java
//  Trial for java
class ankit extends ankitz{
  int i = 0;
}
```



<!--
HOW TO ADD INDENTED IMAGE
![image]({{site.baseurl}}/assets/img/ai_hierarchy.png){: style="float: right"}
-->

<!--
HOW TO ADD A KEY
This is an HTML
example.

*[ANN]: Artificial Neural Network
-->
