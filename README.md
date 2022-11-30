# Ex-6-Handwritten Digit Recognition using MLP
## Aim:
To Recognize the Handwritten Digits using Multilayer perceptron.
##  EQUIPMENTS REQUIRED:
* Hardware – PCs
* Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook
## Theory:
* We have used an MLP to recognize the digits
* A multilayer perceptron (MLP) is a feedforward artificial neural network that generates a set of outputs from a set of inputs. An MLP is characterized by several layers of input nodes connected as a directed graph between the input and output layers. MLP uses back propagation for training the network. MLP is a deep learning method.
* A multilayer perceptron is a neural network connecting multiple layers in a directed graph, which means that the signal path through the nodes only goes one way. Each node, apart from the input nodes, has a nonlinear activation function. An MLP uses backpropagation as a supervised learning technique.
* MLP is widely used for solving problems that require supervised learning as well as research into computational neuroscience and parallel distributed processing. Applications include speech recognition, image recognition and machine translation.
 
**MLP has the following features:**
   * Adjusts the synaptic weights based on Error Correction Rule
   * Adopts LMS
   * Possess Backpropagation algorithm for recurrent propagation of error
   * Consists of two passes
  	   * Feed Forward pass
	   * Backward pass
           
**Learning process** – Backpropagation

**Computationally efficient method**

![image 10](https://user-images.githubusercontent.com/112920679/198804559-5b28cbc4-d8f4-4074-804b-2ebc82d9eb4a.jpg)

**3 Distinctive Characteristics of MLP:**
   * Each neuron in network includes a non-linear activation function<br>
      ![image](https://user-images.githubusercontent.com/112920679/198814300-0e5fccdf-d3ea-4fa0-b053-98ca3a7b0800.png)

   * Contains one or more hidden layers with hidden neurons
   * Network exhibits high degree of connectivity determined by the synapses of the network

**3 Signals involved in MLP are:**
   * Functional Signal
   * input signal
   * propagates forward neuron by neuron thro network and emerges at an output signal
   * F(x,w) at each neuron as it passes

**Error Signal**

   * Originates at an output neuron
   * Propagates backward through the network neuron
   * Involves error dependent function in one way or the other
   * Each hidden neuron or output neuron of MLP is designed to perform two computations:
      * The computation of the function signal appearing at the output of a neuron which is expressed as a continuous non-linear function of the input signal and synaptic weights associated with that neuron
      * The computation of an estimate of the gradient vector is needed for the backward pass through the network

### **TWO PASSES OF COMPUTATION:**

* **In the forward pass:**

   * Synaptic weights remain unaltered

   * Function signal are computed neuron by neuron

   * Function signal of jth neuron is <br>
      ![image](https://user-images.githubusercontent.com/112920679/198814313-2426b3a2-5b8f-489e-af0a-674cc85bd89d.png)<br>
      ![image](https://user-images.githubusercontent.com/112920679/198814328-1a69a3cd-7e02-4829-b773-8338ac8dcd35.png)<br>
      ![image](https://user-images.githubusercontent.com/112920679/198814339-9c9e5c30-ac2d-4f50-910c-9732f83cabe4.png)
   * If jth neuron is output neuron, the m=mL  and output of j th neuron is<br>
      ![image](https://user-images.githubusercontent.com/112920679/198814349-a6aee083-d476-41c4-b662-8968b5fc9880.png)
   * Forward phase begins with in the first hidden layer and end by computing ej(n) in the output layer<br>
      ![image](https://user-images.githubusercontent.com/112920679/198814353-276eadb5-116e-4941-b04e-e96befae02ed.png)


* **In the backward pass,**

   * It starts from the output layer by passing error signal towards leftward layer neurons to compute local gradient recursively in each neuron

   * It changes the synaptic weight by delta rule
      ![image](https://user-images.githubusercontent.com/112920679/198814362-05a251fd-fceb-43cd-867b-75e6339d870a.png)
* Gradient descent is used as an optimisation algorithm here.
* Gradient descent is an iterative first-order optimisation algorithm used to find a local minimum/maximum of a given function.

## Algorithm :
1. Import the necessary libraries of python.

2. After that, create a dataframe and use it in a call to the read_csv() function of the pandas library along with the name of the CSV file containing the dataset.

3. Divide the dataset into two parts. Where the first part is for training and the second is for testing.

4. Define all the basic functions needed to create an MLP.

5. Find the weights and bias of each neuon using the gradient descent algorithm.

6. Make predictions using the defined functions.

7. Create a function to test the predictions which also contains the algorithm to plot the image.

8. NOw, test the predictions and find the accuracy.

## Program:


## Output :


## Result:
