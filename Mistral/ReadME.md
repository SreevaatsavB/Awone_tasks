## Componenets introduced in mistral models


- **[Improvements_in_mixtral.ipynb](Improvements_in_mixtral.ipynb)** is the notebook specifying the new modules added in the mistral models compared to the vanilla transformer and the mistral and mixtral models.

- **[tinymistral_manual](tinymistral_manual.ipynb)** is the notebook containing functions which allow to verify each and every induvidual layer's intermediate output from the huggingface's mistral implementation.


- **[tinymistral_hg.ipynb](tinymistral_hg.ipynb)** is the notebook where the tinymistral model is called for inference, only 1 decoder layer and modified configurations

- **[tinymistral_manual_formatted.ipynb](tinymistral_manual_formatted.ipynb)** contains all the code of manual computation and verification of the model in a well structured format in numpy framework.

- **pytorch_src** :- This directory contains all the modified source code from the huggingface library (print statements were added instead of registering the intermediate outputs)