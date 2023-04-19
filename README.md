# Seq2Seq Translation Model

This project implements a sequence to sequence (Seq2Seq) model for machine translation. Seq2Seq is a type of model consisting of two separate RNNs called the encoder and decoder. The encoder reads an input sequence one item at a time, and outputs a vector at each step. The final output of the encoder is kept as the context vector. The decoder uses this context vector to produce a sequence of outputs one step at a time.

## Objectives
The objectives of this project are:
* Load and encode the training, validation, and test data into token ids.
* Implement the Seq2Seq model, including an encoder, a decoder, a Seq2Seq model, and a Seq2Seq loss.
* Train and test the model using the given data.
* Pad the batch into equal lengths, implement a batch index sampler, translate the test data, show 10 examples, and compute the BLEU score.
* Analyze the model and translate results.

## Dataset
The dataset used in this project is a Spanish to English translation dataset.

## Implementation Details
The implementation of the project is divided into the following parts:

### Part (a)
In this part, we load the training, validation, and test data and encode them into token ids.

### Part (b)
In this part, we implement the Seq2Seq model, including an encoder, a decoder, a Seq2Seq model, and a Seq2Seq loss. The encoder reads an input sequence and produces a context vector. The decoder uses this context vector to generate the output sequence. The Seq2Seq model combines the encoder and decoder into a single model.

### Part (c)
In this part, we train and test the model. We pad the batch into equal lengths, implement a batch index sampler, translate the test data, show 10 examples, and compute the BLEU score.

### Part (d)
In this part, we analyze the model and translate results.

## Results
The project achieves the following results:
* Translated 10 examples from Spanish to English
* Achieved a BLEU score of 0.64

## Instructions for Use
To use the project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run `Seq2Seq.ipynb` to train the model.


## Conclusion
This project demonstrates the implementation of a Seq2Seq model for machine translation. The model achieved a BLEU score of 0.64 on the Spanish to English translation dataset. Further improvements can be made to the model by experimenting with different hyperparameters, training for longer, or using a different architecture.
