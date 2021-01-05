# Lime-Model-Interpretation

## LIME
LIME is model-agnostic, meaning that it can be applied to any machine learning model. The technique attempts to understand the model by perturbing the input of data samples and understanding how the predictions change.

Model-specific approaches aim to understand the black model machine learning model by analysing the internal components and how they interact. In deep learning models, it is e.g. possible to investigate activation units and to link internal activations back to the input. This requires a thorough understanding of the network and doesn’t scale to other models.

LIME provides local model interpretability. LIME modifies a single data sample by tweaking the feature values and observes the resulting impact on the output. Often, this is also related to what humans are interested in when observing the output of a model. The most common question is probably: why was this prediction made or which variables caused the prediction?

Other model interpretability techniques only answer the question above from the perspective of the entire dataset. Feature importance’s explain on a dataset level which features are important. It allows you to verify hypotheses and whether the model is overfitting to noise, but it is hard to diagnose specific model predictions.

## Intuition behind LIME
A key requirement for LIME is to work with an interpretable representation of the input, that is understandable to humans. Examples of interpretable representations are e.g. a BoW vector for NLP, or an image for computer vision. Dense embeddings on the other hand or not interpretable, and applying LIME probably won’t improve interpretability.
The output of LIME is a list of explanations, reflecting the contribution of each feature to the prediction of a data sample. This provides local interpretability, and it also allows to determine which feature changes will have most impact on the prediction.

An explanation is created by approximating the underlying model locally by an interpretable one. Interpretable models are e.g. linear models with strong regularisation, decision tree’s, etc. The interpretable models are trained on small perturbations of the original instance and should only provide a good local approximation. The ‘dataset’ is created by e.g. adding noise to continuous features, removing words or hiding parts of the image. By only approximating the black-box locally (in the neighborhood of the data sample) the task is significantly simplified.


## About me

**Piyush Pathak**

[**PORTFOLIO**](https://anirudhrapathak3.wixsite.com/piyush)

[**GITHUB**](https://github.com/piyushpathak03)

[**BLOG**](https://medium.com/@piyushpathak03)


# 📫 Follw me: 

[![Linkedin Badge](https://img.shields.io/badge/-PiyushPathak-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/piyushpathak03/)](https://www.linkedin.com/in/piyushpathak03/)

<p  align="right"><img height="100" src = "https://media.giphy.com/media/l3URDstnIjBNY7rwLB/giphy.gif"></p>

