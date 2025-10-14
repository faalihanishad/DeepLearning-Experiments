Problem Statement

The objective of this experiment is to design and implement a Sequence-to-Sequence (Seq2Seq) model using Long Short-Term Memory (LSTM) networks for English-to-Hindi machine translation. The task of language translation 
involves converting sentences from a source language to a target language while preserving the semantic meaning. Traditional rule-based methods fail to capture linguistic nuances, making neural network-based approaches 
essential. This experiment aims to demonstrate how encoder-decoder architectures can effectively learn the relationships between languages through character-level translation.

Result

The Seq2Seq model was successfully implemented using TensorFlow Keras. The encoder network processed English sentences into context vectors, while the decoder generated Hindi sentences based on those vectors.
The model was trained for 10 epochs using the Adam optimizer and categorical cross-entropy as the loss function. Despite the small dataset, the model achieved reasonable learning performance, demonstrating that it can map 
simple English phrases like “Hello” → “नमस्ते” and “How are you?” → “तुम कैसे हो?”. The trained model was saved as translation_model.h5 for further use and improvement.


Conclusion

From this experiment, it can be concluded that the Seq2Seq model with LSTM layers is capable of performing basic machine translation tasks by learning the mapping between source and target languages. The encoder-decoder 
mechanism helps in retaining contextual information across time steps, making it suitable for sequential data such as text. Although the experiment used a small dataset for demonstration, it establishes the foundation for 
more complex translation systems using larger datasets and advanced architectures like Bidirectional LSTM or Attention-based Transformers. Thus, Seq2Seq models play a vital role in natural language processing applications 
such as translation, text summarization, and conversational AI.
