# Chapter 3: Coding Attention Mechanisms

### Main Chapter Code

- [ch03.ipynb](ch03.ipynb) contains all the code as it appears in the chapter

### Optional Code

- [multihead-attention.ipynb](multihead-attention.ipynb) is a minimal notebook with the main data loading pipeline implemented in this chapter

### Summary
- This chapter talks about the attention mechanism which includes the multi-head attention mechanisms
- In it, they also talk about how dropout reduces overfitting, how to apply masking for the decoder mechanism.
- They also mentioned what is buffers as well. For more information, do take a look at 03_understanding-buffers.
- They multi-head attention mechanism combines whatever we have learned in the attention mechanism and see how 
each attention block gets combined at the end by applying the foward pass of the last project layer to the context vector.
- In summary, 
Attention(Q, K, V) = Softmax(Q.K^T/ squareroot(dimension of K)) * V