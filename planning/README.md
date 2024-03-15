

# Project Description
------


This project focuses on both Recurrent Neural Networks (RNNs) and Long Short-Term Memory networks (LSTMs) to explore their effectiveness in language-related tasks. We’ll construct a plain RNN model and an enhanced LSTM Encoder-Decoder model. Our journey begins with a proof of concept on an English-French toy dataset, followed by a gradual escalation in complexity with a larger Shona language dataset. Through qualitative and quantitative analyses, we’ll seek to understand these models, assessing their scalability, ability to generalize, errors, and overall performance.

# Project Goals with Timeline
------

## Week 1: Planning

### Goals:
* Complete the project proposal.
* Complete the Project Timeline
* Gather the required data and make preliminary research to ensure the feasibility of the project.

### Update:
All the above tasks have been completed. 

## Week 2 : Prototype Proof of Concept Model on a Toy Data Set 

### Goals:
* Prepare the data through cleaning, involving tasks like reading the data, splitting it, and organizing it into arrays.
* Tokenize the data, providing the flexibility to utilize TensorFlow's full-word tokenizers like WhitespaceTokenizer and UnicodeScriptTokenizer for diverse tokenization options.
* Implement data padding to ensure that both source language sentences and target language sentences have the same length after tokenization.

- #### Proof of Concept:

    *  Construct the Plain RNN model.
    * Train an embedding layer (from Keras): Possible because the toy dataset for dev purposes is small.


**Expected Outcome:** Plain RNN and LSTM on the toy Dataset

### Update:

All the above tasks have been completed. 

### Requests: 

None for now

### Week 3: Slowly Ramp Up the Complexity 


*  Repeat the steps in Phase 1 with a larger Data set of Bambara.
* Apply Transfer Learning: Download weights for the pre-trained embedding model.
* Train both the RNNs and LSTM based Models

**Expected Outcome:** Plain RNN and LSTM on the larger Bambara Dataset

### Update: 

Currently, we have all the models we intend to compare built. We just started testing and have discovered
a few errors/issues with our current implementation. 
Some of the issues that have come up include: 
- While training any of our models, the loss starts really high > 2 does not seem go down significantly
- There are also issues with understanding how tokenization is treating our data
- With tokenization not clear, one of our function that converts model outputs to actual sentences, is also one 
aspect that is still confusing us a little bit. 

- We are currently stuck on the model training. It appears that 
on certain datasets, our models have a high accuracy both on training and validation. However, when given novel examples, they seem to fail in an unusual way. 

### Requests: 

 - Need help with figuring out loss issue
 - Need some help with looking into the tokenization issue
 - We'll need help looking into what's wrong with our models.
 We are hoping that we can stop by office hours for some help. 

Attempt to fix issue and move on to analysis

### Week 4: Qualitative and Quantitative Analysis and Paper


* Cross-Validation to assess the model’s performance and ability to generalize.
* Statistical Analysis: Perform statistical tests evaluating the significance of the results of the plain model (with and without an embedding layer) and the LSTM.
* Prepare a comprehensive paper outlining the experiments run and the results.
* Create a presentation for the class.

### Update:
project done

TBD

### Requests: 

TBD


