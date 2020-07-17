# Deep Learning and Neural Network applications 


Each folder on this repo contains different Deep Learning projects. It includes the primmary code, dataset (for most ones or the link to the dataset) and for some results and README.md for instructions.

- Perceptrons 
- Artificial Neural Network
  - Neurons
  - Weights
  - Biases
  - Activation functions (most used ones) 
- Back prop and Hyperparameters
- Convolutional Neural Network
- Natural Language Processing
- LSTM and Recurrent Neural Network

##### Vanising Gradient Problem

Backpropapagation goes backwards from the output to the input layers, propagating the error gradient. For deeper networks issues can arise from backpropagation, vanishing and exploding gradients!

As you go back to the lower layers, gradients often get smaller, eventually causing weights to never change at lower levels. The opposite can also occur, gradients explode on the way back, causing issues. Not as common as VGP.

