
***Multihead Network:***
  ###### A multi-head deep learning model with multiple classification or output heads. Each of the output heads has a different number of output features corresponding to the number of categories in each label.
		     
		     
***Two branch network (Two Branch Neural Networks):***
   ###### Two branch network use for image matching task. It have two network. First embedding network and matching network structure. 
						
						
**.1 Embedding network:**
   ###### bedding network learn an explicit shared latent embedding space with a maximum-margin ranking loss and novel neighborhood constraints. Compared to standard triplet sampling, we perform improved neighborhood sampling that takes neighborhood information into consideration while constructing mini-batches.
		    
		    
**.2 Matching network:**
  ###### Referred to as a similarity network, fuses the two branches via element-wise product and is trained with regression loss to directly predict a similarity score.
						   
						   
***Inception block:***
		      
   ###### An Inception Module is an image model block that aims to approximate an optimal local sparse structure in a CNN. Put simply, it allows for us to use multiple types of filter size, instead of being restricted to a single filter size, in a single image block, which we then concatenate and pass onto the next layer.

# TYPES OF OPTIMIZERS #

.1 Stochastic Gradient descent

.2 Stochastic Gradient descent with gradient clipping

.3 Momentum.


.4 Nesterov momentum

.5 Adagrad

.6 Adadelta

.7 RMSProp

.8 Adam

.9 Adamax

.10 SMORMS3

### .1 Stochastic Gradient Descent (GD):
                                        Stochastic gradient descent (often abbreviated SGD) is an iterative method for optimizing an objective function with suitable smoothness properties (e.g. differentiable or subdifferentiable). It can be regarded as a stochastic approximation of gradient descent optimization.
					
### .2 Stochastic Gradient descent with gradient clipping:
                                                          Gradient clipping is a technique to prevent exploding gradients in very deep networks, usually in recurrent neural networks.With gradient clipping, pre-determined gradient threshold be introduced, and  then gradients norms that exceed this threshold are scaled down to match the norm.
