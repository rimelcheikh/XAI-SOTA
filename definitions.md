## Explainability
- the degree to which a human observer can understand the reason behind a decision (or a prediction) made by the model (Hoa et al., International Conference on Software Engineering, 2018)

## Interpretability
- the capacity to provide or bring out the meaning of an abstract concept and understandability as the capacity to make the model understandable by end-users (Vilone et Long, Information Fusion, 2021)
- 

## Explanation
- *An explanation is the collection of features of the interpretable domain, that have contributed for a given example to produce a decision (e.g. classification or regression) (Montavon et al., Digital Signal Processing, 2018)

## Interpretation
- *The mapping of an abstract concept (e.g. a predicted class) into a domain that the human can make sense of (Montavon et al., Digital Signal Processing, 2018)

## important feature 
- class specific feature (Wilming et al. 2022)

## Counterfactual Explanations 
- a class of model interpretation methods that seek to answer: what perturbations to the input are needed for a model’s prediction to change in a particular way? (Abid et al. 2022)


# Requirements for explainability/interpretability
- fidelity : "the representation of inputs and models in terms of concepts should preserve and present to end-users their relevant features and structures" (Alvarez-Melis et Jaakkola, 2018)
- diversity : "inputs and models should be representable with few non-overlapping concepts" (Alvarez-Melis et Jaakkola, 2018)
- grounding : "concepts should have an immediate human-understandable interpretation" (Alvarez-Melis et Jaakkola, 2018)
- contrastive nature of explanations : "people seek for an explanation when they are presented with counterfactual and/or counterintuitive events" (Miller, 2019)
- selectivity of explanations : "people usually do not expect that an explanation contains the actual and complete list of the causes of an event, but only a selection of the few causes deemed to be necessary and sufficient to explain it" (Miller, 2019)
- social nature of explanations : "explanations are part of a dialogue aiming at transferring knowledge, therefore, they are based on the beliefs of both the explainer and explainee" (Miller, 2019)
- irrelevance of probabilities to explanations : "referring to the occurrence probabilities of events or to the statistical relationships between causes and events does not produce a satisfactory and intuitive explanation. Explanations are more effective when they refer to the causes and not to their likelihood" (Miller, 2019)
- graphical integrity : "the representations should highlight the features that contribute the most to the final predictions and distinguish those with positive and negative attribution" (Sundararajan et al., IUI Workshops, 2019)
- coverage : "a large fraction of the most important features should be visible in the representation" (Sundararajan et al., IUI Workshops, 2019)
- morphological clarity : "the important features should be clearly displayed, their visualisation cannot be ‘noisy’" (Sundararajan et al., IUI Workshops, 2019)
- layer separation : "the representation cannot occlude the raw image which should be visible for human inspection" (Sundararajan et al., IUI Workshops, 2019)
- input invariance : "a method for explainability must mirror the sensitivity of the underlying model with respect to transformations of the inputs in order to ensure a reliable interpretation of their contribution to each prediction" (Kindermans et al., NIPS Workshop on Explaining and Visualizing Deep Learning, 2017)
- implementation invariance : a method applied to functionally equivalent neural networks should assign identical contributions to the features of the input (Sundararajan et al., 2017)
