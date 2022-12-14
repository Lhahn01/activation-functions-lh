# Activation Functions - Neural Networks
**Name:** Lauren Hahn

## To Do:
- [x] Visual representation of all the activation functions
- [x] Experiment with different activation functions with a simple MLP problem
- [x] Compare between ReLU and Leaky ReLU (vanishing gradients)
- [x] Identify how Leaky ReLU deals with dead neurons

## Description
The project that I have selected is one of the pre-approved ones, where I would run a
comprehensive analysis of different activation functions. By doing so, I will determine which of the functions provide the most stability or performance enhancements. Some of the activation functions to compare are...
- Rectified Linear Unit (ReLU)
- Leaky ReLU
- Parametric ReLU Activation Function
- Exponential Linear Unit (ELU)

## Research
***What is my goal?***

The goal of my project is to compare the activation functions, specifically those used between hidden layers. With those, I will be figuring out at which situations (when and where) each of the activation function works the best. A possible situation to look at is that some people say to use Leaky ReLU over ReLU when trying to solve the problem of vanishing gradients in ReLU. But what does that mean/entail (is leaky ReLU actually preferred in that situation)? Something else to investigate is whether leaky ReLU is actually the best when dealing with dead neurons (and which one specifically).

***What is Activation Function? Why is it important?***

Based on the lecture slide, these are “what determine if one of our neurons/nodes fires/matters.” By interpreting the inputs and weights of a given network, it will see if there’s an output. Activation function is important because it allows a neural network’s prediction to be more accurate depending on the type used.[^1] For example, a simple linear function may be simple and easy, however it provides a limited performance and power most of the times. They won’t be able to “learn and recognize complex mappings from data.”[^2]

***What is rectified linear unit (ReLU)?***

This is one of the activate functions that is most widely used in neural network. According to this, when x is less than or equal to 0, it results into 0. On the other hand, when x is greater than 0, it results into the same value x was. According to the lecture, this function solves several problems that were seen in other functions. It provides a mean to turn a network on or off. That is, a neuron will be deactivated when the output of linear transformation is zero.[^3] Apparently one of the reasons why ReLU is more efficient compared to others is because all the neurons are not activated at the same time. Instead, certain number of them are activated at a time.

***What is leaky ReLU?***

This specific activate function is a slight modification to the original ReLU function. Rather than having a neuron be deactivated, the neuron’s signal is suppressed. When x is less than or equal to 0, we multiply x by a which is usually a fractional value. And like the original ReLU function, when x is greater than 0, it results into the same value x was. This specific function prevents the scenario when a node might never fire.

***What is parametric ReLU?***

This activation function is another varient of ReLU but the alpha of the function is not assigned to us. Instead, it's a parameter that's learn along with weights and biases during the training period.

## Few of the Sources
https://www.ijeast.com/papers/310-316,Tesma412,IJEAST.pdf 

This research paper was very helpful in understanding a bit more of the different activation functions as well as the purpose of them when working with neural networks. Another great thing with this paper was that it showed a graph for each of the function to help better understand what the authors were trying to tell us. Sometimes it’s easier to decipher a graph than read a person’s description of how the graph looks like or even looking at an equation. 

https://towardsdatascience.com/the-importance-and-reasoning-behind-activation-functions-4dc00e74db41

This article was also great as it helped assist me understand the activation functions a bit more outside of a research paper. It was a lot clearer to see the advantages and disadvantages that some of these different activation functions have. 

https://www.geeksforgeeks.org/activation-functions-neural-networks/

This page was also a great source for additional help of understanding the activation functions. I liked how they organized the information when talking about the variety of activation functions as it was easier to comprehend right away. For example, the “uses” column was great in helping me figure out what each activation function may be used over others. 

https://arxiv.org/pdf/1511.07289.pdf

The research paper was great in understanding a bit more of what ELU is and how it compares to existing activation functions. It specifically addresses how it is different from ReLU as well as any variants of it. 




[^1]: https://www.ijeast.com/papers/310-316,Tesma412,IJEAST.pdf
[^2]: Ibid.
[^3]: Ibid.
