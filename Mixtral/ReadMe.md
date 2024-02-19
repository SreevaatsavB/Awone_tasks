## Componenets introduced in Mixtral 8X7B model



- **[tinymixtral_manual](tinymixtral_manual.ipynb)** is the notebook containing functions which allow to verify each and every induvidual layer's intermediate output from the huggingface's mixtral implementation.


- **[tinymixtral_hg.ipynb](tinymixtral_hg.ipynb)** is the notebook where the tinymixtral model is called for inference, only 1 decoder layer and modified configurations

- **pytorch_src** :- This directory contains all the modified source code from the huggingface library (print statements were added instead of registering the intermediate outputs)