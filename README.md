# The Forward-Forward Algorithm proposed by Geoffrey Hinton - Unsupervised Learning Version

## What is Forward Forward Algorithm?

The Forward-Forward algorithm is a learning procedure for neural networks that replaces the forward and backward passes of backpropagation by two forward passes, one with positive data and the other with negative data. Each layer has its own objective function which is simply to have high goodness for positive data and low goodness for negative data. The sum of the squared activities in a layer can be used as the goodness but there are many other possibilities. 

For more information, see: [The Forward-Forward Algorithm: Some Preliminary
Investigations](https://www.cs.toronto.edu/~hinton/FFA13.pdf)

## Implementation

I have implemented the unsupervised version of the Forward-Forward algorithm for PyTorch, while attempting to stay faithful to the details outlined in the research paper.

## Contact

If you have any questions or would like to discuss this work further, please do not hesitate to contact me via [email](i_konak@hotmail.com) or [LinkedIn](https://www.linkedin.com/in/ismail-konak/).
