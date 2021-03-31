
***Multihead Network:***
                     A multi-head deep learning model with multiple classification or output heads. Each of the output heads has a different number of output features corresponding to the number of categories in each label.
		     
		     
***Two branch network (Two Branch Neural Networks):***
                                                Two branch network use for image matching task. It have two network. First embedding network and matching network structure.
						
						
**.1 Embedding network:**
                    Embedding network learn an explicit shared latent embedding space with a maximum-margin ranking loss and novel neighborhood constraints. Compared to standard triplet sampling, we perform improved neighborhood sampling that takes neighborhood information into consideration while constructing mini-batches.
		    
		    
**.2 Matching network:**
                                                   Referred to as a similarity network, fuses the two branches via element-wise product and is trained with regression loss to directly predict a similarity score.
						   
						   
***Inception block:***
		      An Inception Module is an image model block that aims to approximate an optimal local sparse structure in a CNN. Put simply, it allows for us to use multiple types of filter size, instead of being restricted to a single filter size, in a single image block, which we then concatenate and pass onto the next layer.

# TYPES OF OPTIMIZERS #

#.1 Gradient Descent (GD)#
.2 Stochastic Gradient Descent.
.3 Mini-Batch Gradient Descent.
.4 Momentum Based Gradient Descent.
.5 Nesterov Accelerated Gradient (NAG)
.6 Adagrad.
.7 RMSProp.
