# Activation Functions - Neural Networks
**Name:** Lauren Hahn

## Description
The project that I have selected is one of the pre-approved ones, where I would run a
comprehensive analysis of different activation functions. By doing so, I will determine which of the functions provide the most stability or performance enhancements. Some of the activation functions to compare are...
- Rectified Linear Unit (ReLU)
- Leaky ReLU
- Parametric ReLU
- Exponential Linear Units (ELU)
- Gaussian Error Linear Unit (GELU)
- Scaled Exponential Linear Unit (SELU)

## Research
***What is my goal?***

The goal of my project is to compare the activation functions, specifically those used between hidden layers. With those, I will be figuring out at which situations (when and where) each of the activation function works the best. A possible situation to look at is that some people say to use Leaky ReLU over ReLU when trying to solve the problem of vanishing gradients in ReLU. But what does that mean/entail (is leaky ReLU actually preferred in that situation)? Another possible factor to look at is speed or computational time, where I can see which one may be faster compared to others. Something else to investigate is whether leaky ReLU or parametric ReLU are actually the best when dealing with dead neurons (and which one specifically).

***What is Activation Function? Why is it important?***

Based on the lecture slide, these are “what determine if one of our neurons/nodes fires/matters.” By interpreting the inputs and weights of a given network, it will see if there’s an output. Activation function is important because it allows a neural network’s prediction to be more accurate depending on the type used.[^1] For example, a simple linear function may be simple and easy, however it provides a limited performance and power most of the times. They won’t be able to “learn and recognize complex mappings from data.”[^2]

***What is rectified linear unit (ReLU)?***

This is one of the activate functions that is most widely used in neural network. According to this, when x is less than or equal to 0, it results into 0. On the other hand, when x is greater than 0, it results into the same value x was. According to the lecture, this function solves several problems that were seen in other functions. It provides a mean to turn a network on or off. That is, a neuron will be deactivated when the output of linear transformation is zero.[^3] Apparently one of the reasons why ReLU is more efficient compared to others is because all the neurons are not activated at the same time. Instead, certain number of them are activated at a time.

***What is leaky ReLU?***

This specific activate function is a slight modification to the original ReLU function. Rather than having a neuron be deactivated, the neuron’s signal is suppressed. When x is less than or equal to 0, we multiply x by a which is usually a fractional value. And like the original ReLU function, when x is greater than 0, it results into the same value x was. This specific function prevents the scenario when a node might never fire.

***What is parametric ReLU?***

The following is the mathematical representation of parametric ReLU.


[^1]: https://www.ijeast.com/papers/310-316,Tesma412,IJEAST.pdf
[^2]: Ibid.
[^3]: Ibid.
