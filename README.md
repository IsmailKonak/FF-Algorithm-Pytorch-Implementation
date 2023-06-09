# The Forward-Forward Algorithm proposed by Geoffrey Hinton - Unofficial Pytorch Implementation

## What is Forward Forward Algorithm?

The Forward-Forward algorithm is a learning procedure for neural networks that replaces the forward and backward passes of backpropagation by two forward passes, one with positive data and the other with negative data. Each layer has its own objective function which is simply to have high goodness for positive data and low goodness for negative data. The sum of the squared activities in a layer can be used as the goodness but there are many other possibilities. 

For more information, see: [The Forward-Forward Algorithm: Some Preliminary
Investigations](https://www.cs.toronto.edu/~hinton/FFA13.pdf)

<br>

## Implementation

I have implemented the Forward-Forward algorithm for PyTorch, while attempting to stay faithful to the details outlined in the research paper. If you encounter any discrepancy or issue, please do not hesitate to contact me.





<br>

## To Do

- [x] [Forward Forward Algorithm - Unsupervised](https://github.com/IsmailKonak/FF-Algorithm-Pytorch-Implementation/tree/main/FF%20-%20Unsupervised/MLP)
- [ ] Forward Forward Algorithm - Supervised
- [x] [Forward Forward Algorithm CNN - Unsupervised](https://github.com/IsmailKonak/FF-Algorithm-Pytorch-Implementation/tree/main/FF%20-%20Unsupervised/Conv)
- [ ] Forward Forward Algorithm -Unsupervised (not layerwise training)
- [ ] Forward Forward MLP - Supervised (not layerwise training)

<br>
<br>

## Contact

If you have any questions or advices, or you would like to discuss this work further, please do not hesitate to contact me via [email](i_konak@hotmail.com) or [LinkedIn](https://www.linkedin.com/in/ismail-konak/).
