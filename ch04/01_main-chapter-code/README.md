# Chapter 4: Implementing a GPT Model from Scratch To Generate Text

### Main Chapter Code

- [ch04.ipynb](ch04.ipynb) contains all the code as it appears in the chapter
- [previous_chapters.py](previous_chapters.py) is a Python module that contains the `MultiHeadAttention` module from the previous chapter, which we import in [ch04.ipynb](ch04.ipynb) to create the GPT model

### Optional Code

- [gpt.py](gpt.py) is a standalone Python script file with the code that we implemented thus far, including the GPT model we coded in this chapter

### Summary
- Implementation of the feed-forward neural network after the multi-attention head block.
- Introduces the concept of ReLU activation function and why it is preferred over ReLU.
- Adding shortcut connections and its benefits. This is to mitgate the vanishing gradient problem.
- Applying Layer Normalization helps to stabilize training and enable faster convergence to effective weights. The layer normalization is applied before and after the multi head attention module.