# Kubeflow examples
Gathering of scripts and models to get the most out of kubeflow

The following test have been performed on a TensorFlow1.6 notebook, running on Kubeflow 0.6.2:

| \ | py notebook | mixed language job | tensorflow / keras | pytorch | sklearn | xgboost | onnx | TensorRT | 
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|**manual pipeline**|A1,A2,A3|to do|d|e|f|g|h|i|
|**kale pipeline**|C1|to do|C2|C3|C4|to do|to do|to do|
|**training**|A|to do|D1,C2|e,C3|C4|g|h|i|
|**tuning**|A|to do|D|e|f|g|h|i|
|**seldon serving**|A|to do|d|e|f|g|h|i|
|**kfserving**|A|to do|d|e|f|g|h|i|
|**tfserving**|A|to do|d|e|f|g|h|i|
|**fairing**|A|to do|d|e|f|g|h|i|

Check on: 
- GPU use
- Parallel/distributed processing
- Multitenant behaviour



### A. Py3 notebook examples (using pipeline definitions):
1. [Pipeline introduction](./03-pipelines/Pipeline_Intro.ipynb)
2. [Create a lightweight Python pipeline](./03-pipelines/Pipeline_Simple.ipynb)
3. [Data passing in python components](./03-pipelines/Data_passing_in_python_components.ipynb)
4. [Simple notebook pipeline using base image](./03-pipelines/simple-notebook-pipeline_[TF2]/Simple_Notebook_Pipeline.ipynb)

### B. Mixed language examples
1. No examples yet

### C. Kale examples (automatic conversion with correct annotations)
1. [Basic kale example](./03-pipelines/kale/base/candies_sharing.ipynb)
2. [TensorFlow taxi-cab-classification](./03-pipelines/kale/taxi-cab-classification_[TF]/taxicab_pipeline.ipynb)
3. [PyTorch classification](./03-pipelines/kale/pytorch-classification_[PyTorch]/cifar10_classification.ipynb)
4. [Sci-kit Learn titanic ML dataset](./03-pipelines/kale/titanic-ml-dataset_[sklearn]/titanic_dataset_ml.ipynb)

### D. TF+Keras examples:
1. [Basic training and model export Keras (mnist)](./02-environment-jupyter-mgt/Explore_Notebook_Development.ipynb)

### E. PyTorch examples
1. No examples yet

### F. Sci-kit Learn examples
1. No examples yet

### G. xgboost examples
1. No examples yet

### H. ONNX examples
1. No examples yet

### I. TensorRT examples
1. No examples yet