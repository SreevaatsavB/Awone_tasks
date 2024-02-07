## Vanilla transformer Enc_Dec architecture

### Cross verification of pytorch implementation 


- **[DecOnly.ipynb](DecOnly.ipynb)** is the notebook containing functions whcih allow to verify each and every induvidual layer's intermediate output from the torch's transformer implementation for the decoder only model. 
\
We first create a transformer model with the torch's EncoderLayer with src_mask whcih acts the same as block from the decoder only model (Ex :- GPT) and then validate the outputs using the initialised model's parameters and inputs. 

The we train the model for an epoch and validate all the intermediate outputs of the model.

#### NOTE:- 
The pytorch source files from transformers library for this code are the same as those of Vanilla_Enc_Dec.
