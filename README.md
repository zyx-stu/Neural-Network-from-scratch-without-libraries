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



