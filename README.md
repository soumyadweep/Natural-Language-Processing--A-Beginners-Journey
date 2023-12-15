# Natural-Language-Processing--A-Beginners-Journey  
Specifically designed for those who want to learn from scratch.  


## Why do we need RNN?  
Ans: ANN can't capture sequential information. The problem with sequential data like text is that each sentence has a different length i.e. some sentence has 5 words, some other sentence may have 7 words. So how do you design a Neural Network where the oinput layer can take input of different lengths. To address these issues an architectural change was needed. That architectural change came in the form of a RNN(Recurrent Neural Network).  
Click [here](https://youtu.be/4KpRP-YUw6c?si=vo7dkM95JYM3x9e1) to see the youtube video where you will get demonstration of the above idea.

## What is the difference between ANN and RNN?  
One of the major differences is that in ANN data is fed at once, but in RNN data is fed sequentially, one by one.The second difference is that in RNN during forward propagation the output in the hidden layer is again fed back into that layer as input,this is called state whereas in ANN the concept of state is not there.  

