# Section II. Summary Paper

## Evolution of Machine Learning

Advances in machine learning (ML), particularly deep neural networks (DNNs), have allowed us to extract and use the extensive information in unstructured data for applications in public and private sectors. In the banking area, these include modeling and analysis of text data on customer communications, complaints, emails, etc. However, the complexity of the underlying ML algorithms makes the results hard to interpret and explain to users and regulators. 


## Why ML Explainability

ML programs interpret the data with algorithms to predict an event without knowing why. Therefore it is important for ML creators and users to understand the predictions in human terms with transparency.  

## What Explainable Models are in Use:

For the project;

->Shapley is recommended for tabular and non-differentiable models, which is the case in AutoML Tables models consisting of meta-ensembles of trees and neural networks.

->LIME is a ML model agnostic method by testing the ML model results when certain aspects are changed within the model. 

## Explaining ML Classifiers with Lime

Machine learning algorithms can produce impressive results in classification, prediction, anomaly detection, and many other hard problems. Understanding what the results are based on is often complicated, since many algorithms are black boxes with little visibility into their inner working.

The idea of LIME is to give it a single datapoint, and the ML algorithm to use, and it will try to build understandable explanation for the output of the ML algorithm for that specific datapoint. Such as “because this person was found to be sneezing and coughing (datapoint features), there is a high probability they have a flu (ML output)”.

The idea is to reduce bias while increasing correctness of the model i.e Did the model use arrive at similar features to prediction the results as humans do?

The other part is for future use. Human comprehension, improvement of the model. Making it robust (ability to note intereference as intentional or unintentional) and transfarable.


## Conclusion

CNN SHAP fully utilizes the advantage of SHAP explanation in computing local feature importance, but avoids the curse of high feature dimensionality in explaining NLP tasks. By applying de-duplication in CNN SHAP output, we are able to provide more understandable and meaningful explanations of the model. We also proposed global explanation based on CNN SHAP, which quantifies the importance of n-grams globally.

Another potential usage of CNN SHAP is as a surrogate explanation method approximating any text classification models, especially those much more complicated DNN models, using CNN and using the techniques here to explain the results. However, more work needs to be done to evaluate the performance of CNN SHAP as a surrogate explanation method. In addition, the method uses marginal expectations to ease the computational burdens in evaluating the conditional expectations in the SHAP formula in equation. This can perform poorly in some applications, so it in necessary to explore alternatives.

## Reference
https://arxiv.org/ftp/arxiv/papers/2008/2008.11825.pdf


