# Building a Language Model

This notebook contains both notes developing a ground-up mathematical description of language models, and a working code demonstration. 

The point here is to build up and understand the language modeling problem in general, and build something grounded in foundational approximation methods. The resulting non-softmax-attention-transformer model is implemented in PyTorch and tested on generating Shakespeare - it works as expected.

There's nothing new under the sun, but as of writing I have not found where in the (noisy) ML literature one would find something equivalent to the model implemented here. Its probably one of these "state-space models", but the correspondence is very unclear from cursory inspections.
