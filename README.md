## Sentence-Classification-Using-Pytorch

![Thanks to Ben Trevett](https://github.com/bentrevett)

### Objective 
    
    The objective is to learn Pytorch along with implementing the deep learning architecture like vanilla RNN, BiLSTM, FastText architecture for Sentence Classification with Custom dataset using torchtext.

### Vanilla RNN Pointers
  * Novel Architecture for sequence modeling.
  * Major difference between vanilla neural network and RNN - Input to hidden layer at time step (t) is combination of input (x_t) and hidden units from previous 
    time step (h_t-1).
  * Problem with vanilla RNN is Vanishing Gradient, during backpropagation the gradients tends to become very small and the model tend lose learned parameters.
  * Cannot be applied for long sequence of text.
   

### BiDirectional LSTMs Pointers
  * Major difference between vanilla RNN network and LSTMs - Input to hidden layer at time step (t) is combination of input (x_t) and hidden units from previous 
    time step (h_t-1) and cell unit (c_t-1).
  * Cell unit is a memory unit, which controls the flow of information i.e. dropping and retaining of parameters take places.
  * Bidirectional means the model takes in two RNN layers of input:
    * First, sequence of words from first word and last word, it has its parameters like hidden and cell units.
    * Second, sequence of words from last word and first word, it has parameters like hidden and cell units.
  * The prediction happens on the output of both hidden units. F(h_f_t, h_b_t), forward(f) and backward(b).
  
      
        To be continued
    
   
