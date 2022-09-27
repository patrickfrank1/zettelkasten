# 3 common strategies to measure bias in NLP problems

url: <https://towardsdatascience.com/3-common-strategies-to-measure-bias-in-nlp-models-2022-b948a671d257> \
tags: bias, nlp, explainability

- bias = skew in the data that produces a type of harm
- there is no single measure of bias
- choose bias metric based on model type and application

Curated data sets:

- inference on data sets that are specifically designed to detect a specific bias
- e.g. Maybe Ambiguous Pronom (MAP) data set, WinoBIAS, WinoGender, ...
- human labeled, i.e. god standard

Accuracy across subgroups:

- explore model-level error across subgroups
- if subgroup information is not available, can run classification models over dataset samples to produce them

Perturbation and counterfactuals

- perturb the inputs of your model and observe the outputs
- find bias on the prediction level (as opposed to the model level as above)
- e.g. delete exactly one word from the sample
- idea is also used by LIME and SHAP to predict feature importance
