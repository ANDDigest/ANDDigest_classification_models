# ANDDigest_NN_Classifiers
This repository contains classification models, used for the [ANDDigest](https://anddigest.sysbio.ru/) project.

## Notebooks with a code
This **notebook** [![Open In Colab](images/colab.svg)](https://colab.research.google.com/github/ANDDigest/ANDDigest_classification_models/blob/main/notebooks/PubMedBERT_finetuning.ipynb) can be used for the fine-tuning of the classification models for the binary classification of the names of biological entities for ANDDigest, the code was developed on the basis of the
_McCormick, Chris, and Nick Ryan. "Bert fine-tuning tutorial with pytorch." Retrieved January 24 (2019): 2021._


Please keep in mind, that in order to repeat a fine-tuning, as it was done in the manuscript, the same dataset should be downloaded, and valid pathes to the correspond files from the dataset need to be specified within the notebook.

This **notebook** [![Open In Colab](images/colab.svg)](https://colab.research.google.com/github/ANDDigest/ANDDigest_classification_models/blob/main/notebooks/ANDDigest_predictions_cuda.ipynb) can be used for the application of the fine-tuned classifiers.

## Examples
The **examples** folder contains positive and negative input and output examples, used for the classification of the short names of cell components.


## Gold Standards
The Gold Standards folder contains 2 subdirectories, a first one, entitled ANDSystem, contains data used for the main assesement of the accuracy for each developed model, as it is described in the manuscript. The Other subfolder contains input and output data, that was generated using the existing gold standards.


## Data availability

All the datasets used for the fine-tuning are freely available, and can be downloaded from the datasets section via the following [**link**](https://huggingface.co/Timofey). The models section contains the fine-tuned models used as a part of AI NER module in ANDDigest.

## Citing
If you found ANDDigest, or the developed models, to be useful in your research, please cite the following articles:

```
Ivanisenko, T.V., Saik, O.V., Demenkov, P.S. et al. ANDDigest: a new web-based module of ANDSystem for the search of knowledge in the scientific literature. BMC Bioinformatics 21 (Suppl 11), 228 (2020). https://doi.org/10.1186/s12859-020-03557-8
Ivanisenko, T.V.; Demenkov, P.S.; Kolchanov, N.A.; Ivanisenko, V.A. The New Version of the ANDDigest Tool with Improved AI-Based Short Names Recognition. Int. J. Mol. Sci. 2022, 23, 14934. https://doi.org/10.3390/ijms232314934
```
