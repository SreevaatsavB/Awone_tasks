## Vanilla transformer 

### Cross verification of pytorch implementation 


- **[Enc_Dec_MH_mask_train.ipynb](Enc_Dec_MH_mask_train.ipynb)** is the notebook containing functions whcih allow to verify each and every induvidual layer's intermediate output from the torch's transformer implementation, with masked attetion example. 
\
We first create a transformer model specific encoder, decoder layer from torch and the validate the outputs using the initialised model's parameters and inputs. 

- **pytorch_src** :- This directory contains all the modified source coder from the pytorch library (print staements were added instead of registering the intermediate outputs)

