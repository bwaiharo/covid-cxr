# EXPLAINABILITY
### Prof. Pantelis Monogioudis
### Benedict Waiharo

## Setup

AWS instance type: g4dn.2xlarge, 8 cpu, 32 GB, 1 T4 gpu, 16 GB

OS Linux 18.04.1-Ubuntu

source activate tensorflow2_latest_p37

export PATH=/opt/tljh/user/bin:$PATH


Forked Project https://github.com/aildnont/covid-cxr

## 1 

First you find this this implementation of the method called Local Interpretable Model-Agnostic Explanations (i.e. LIME). You also read this article and you get your hands dirty and replicate the results in your colab notebook with GPU enabled kernel(40%).

Notebook: [lime_explain.py](src/interpretability/lime_explain.py)

Run results: [Results](results)


## 2

To Do: A fellow AI engineer, tells you about another method called SHAP that stands for SHapley Additive exPlanations and she mentions that Shapley was a Nobel prize winner so it must be important. You then find out that Google is using it and wrote a readable white paper about it and your excitement grows. Your manager sees you on the corridor and mentions that your work is needed soon. You are keen to impress her and start writing your 3-5 page summary of the SHAP approach as can be applied to explaining deep learning classifiers such as the ResNet network used in (1). (40%)

Source: https://storage.googleapis.com/cloud-ai-whitepapers/AI%20Explainability%20Whitepaper.pdf

Result: [summary.md](summary.md)

Forked Project: Add SHAP to existing x-ray model in https://github.com/aildnont/covid-cxr


## 3 

To Do: After your presentation, your manager is clearly impressed with the depth of the SHAP approach and asks for some results for explaining the COVID-19 diagnoses via it. You notice that the extremely popular SHAP Github repo already has an example with VGG16 network applied to ImageNet. You think it wont be too difficult to plugin the model you trained in (1) and explain it. (20%)


Notebook: [shaptrain.ipynb](src/shaptrain.ipynb)




    
   


