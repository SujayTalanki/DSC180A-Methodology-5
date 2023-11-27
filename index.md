# Sujay Talanki (stalanki@ucsd.edu)

## B13: Stochastic Optimization in Over-Parameterized Models: Neural Networks and Kernel Machines with Misha Belkin and Yian Ma

1. What is the most interesting topic covered in your domain this quarter?

   **The most interesting topic we have discovered in our domain is the Neural Networks and LLM's. These two concepts are the main focal points of
   modern machine learning and deep learning. At the beginning of the quarter, we talked about the differences between over-parameterized and
   under-parameterized loss landscapes (they have different conditions for convergence under SGD!). We also talked about early stopping and feature learning.
   We didn't specifically talk about LLM's in the section, but our group is working on optimizing a NanoGPT model, which is an LLM in itself. The work we have
   done with this model has been the most interesting part, as we can emulate an effective GPT model on such a small scale (using 1 GPU!). This has been the most
   interesting part.**
   
2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.

   **A potential investigation that I would like to pursue for next quarter is designing an optimal neural network architecture for a machine learning task.
   I have taken DSC 140B, and in this class we dive a little bit into neural network design, but the choices for neural network depth amd width seemed 
   somewhat arbitrary. I feel learning the optimal width and depth of a neural network for each application would be a useful tool to posess for future
   data science jobs and applications. This task would also fit under the description of our capstone section!**
   
3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?

   **We were somewhat restricted by our options in our Quarter 1 Project. We had 4 projects to choose from, and the content of these projects didn't seem
   the most interesting to me. Our project is to change the loss function of an existing NanoGPT model to see if we can improve performance. We are also asked
   to change some of the hyperparamters to see if we can improve the performance. The NanoGPT model uses cross entropy for the loss function, and this seems to
   work well for the current application! It doesn't hurt to try the MSE loss function, but it seems like this current loss function works well for the LLM
   architecture. I think there are other tasks in the field of deep learning and neural network theory that could've been more applicable to our future jobs.**
   
4. What other techniques would you be interested in using in your project?

   **We haven't implemented this yet, but I would like to combine some of the principles used in DSC 102 (distributed computing and parallel task processing)
   to run our model. We haven't really been taught how to implement this on our DSMLP servers, but I feel like these techniques would helpful to know for
   our careers and can significantly reduce the time it takes to run large queries/models on large amounts of data. Our NanoGPT model can run on a small scale,
   but it still takes much time to run the model on a limited number of GPU's. Utilizing multiple nodes and employing parallel processing would significantly
   speed up the training process and would be helpful to know!**

