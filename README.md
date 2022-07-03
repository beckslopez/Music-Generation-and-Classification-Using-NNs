# Music-Generation-and-Classification-Using-NNs

Understanding audio data continues to present a challenge in the field of
deep learning due its high dimensionality. Often audio is converted to
images through spectrograms or wave plots to utilize the great success in
established architectures for classifying and generating visual information.
For our deep learning project, we develop two networks to explore mu-
sic generation and classification tasks. 

The first network would generate music of a specified genre using recursive techniques on the sequential audio training data. The second network would utilize image classification
mechanisms and convolutional network architecture to process the gener-
ated music data. This network would be trained on the original dataset
used to train the audio generation network.
For these tasks, we chose to use the GTZAN Dataset which features a
variety of audio from 2000-2001. This audio is divided into 10 genres with
100 thirty second music clips each.

We utilize various network types and layer kinds:
• Fully connected: Feeds an input forward by multiplying it by a weight
vector and adding a bias
• Convolutional: Apply filters to an input in order to create a feature
map that summarizes presence of detected features in such input
• Recurrent: Utilizes past memory to feed forward an input
  - Long Short Term Memory: Learn long-term order dependence for sequence predication problems
using input, forget, and output gate
  - Gated Recurrent Unit: Uses previous hidden states on input to produce output using reset and
update gate
  - Bi-directional: Connect two hidden layers of opposite directions back to the same output.
  
Please see research poster and paper for more details on the archetitecture and details of the networks.
