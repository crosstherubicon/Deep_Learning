
## Vanising Gradient Problem

Backpropapagation goes backwards from the output to the input layers, propagating the error gradient. For deeper networks issues can arise from backpropagation, vanishing and exploding gradients!

As you go back to the lower layers, gradients often get smaller, eventually causing weights to never change at lower levels. The opposite can also occur, gradients explode on the way back, causing issues. Not as common as VGP.
