# Transfomer_implementation

# Understand basics of transfomer
Language model is predicting or recovering the next word. Before transfomer, RNN is the mostly used for natural language model. However, there were several weakneses. 
1. Long range dependencies 
 - it's hard to look back if the sequence data is too long. 
2. Number of training steps, gradient vanishing
- RNN looks all the input data one by one. So the sequence data is too long, there would be so many parameters to optimize. Then it needs a lot of steps to train.
3. Non pararell computation 
- As mentioned in 2, it's recurrent computation 

However, transfomer architecture deals with these RNN problems as below:
1. Make connections to every part of sequence. 
2. The computation is done simultaneously, no need lots of layers, which results in no gradient vanishing.
3. it's pararell computation(GPU)


# Attention Mechanism
Given 
