# Neural-Network-from-scratch-without-libraries
i am going to design a neural network from basic building blocks . Also , i am not going to use any pytorch or tensorflow or keras 
  
step 1 :- I used spiral data and used 3 classes
  
step 2 :- Layers , Activation fucntions and Loss     
  
For all these 3 we will implement through Forward Pass and Backward Pass  
  
Forward Pass:- input-->neuron layers-->Computaion (DOTproduct+Bias)-->activation--> Loss     
  
Dot Product at each layer          
I/P X=[x1,x2,x3,......,Xn], Weights W= [[W11,W21,W31,....Wnm],.....[W1m,W2m,......Wnm]], Bias B=[b1,b2,...,bn]                    
Output= X*W+B--> np.dot(X,W)+B             


Backward Pass:- We calculate parital derivative at layer with repective output on Input, weights and bias applied for calculating that output..   
  
Acitvation FUncitons:- O/P layer--> Soft-max funciton and Hidden_Layers--> ReLU  
  
  
Softmax function --> Gives the Likelihood/probability of the label in Range [o,1].. which becomes quiet easy to classify by doing this.  
  
Loss--> Using Catergorical cross entropy loss  
  
For case of backward pass in  activaiton funciton it very complex so we are going to combined BACKWARD_PASS(LOSS + ACTIVATION_SOFTMAX) it is == Prediction -- GroundTruth   
    
So till now we find paritial derivates of weights and activation fucnction so now the questioin is--   HOW DO WE OPTIMIZE THE WEIGHTS ? ---> OPTIMIZERS (adam)-->combines the advantages of MomentumGD+RMSpropGD   


  As everything completed regarding architecting the Neural Network we have to now TRAIN our Network..







