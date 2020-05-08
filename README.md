# mailbot-demo-01
https://techcommunity.microsoft.com/t5/ai-customer-engineering-team/deep-learning-with-bert-on-azure-ml-for-text-classification/ba-p/1149262

## Local enviroment setup
### Anaconda & Jupiter Notebooks
1. Install Anaconda
2. Create the `mailbot-demo-01` environment using Anaconda navigator
3. Activate the environment with the shell command:
```
conda activate mailbot-demo-01
```
4. Enable environment-specific IPython kernels.This will ensure expected kernel and package import behavior when working with Jupyter Notebooks within Anaconda environments
```
conda install notebook ipykernel
```
5.  Create the kernel
```
ipython kernel install --user --name mailbot-demo-01 --display-name "Python (mailbot-demo-01)"
```
6.  Install the base Azure Machine Learning SDK with notebook and automl extras
```
pip install azureml-sdk[notebooks,automl]
```
### Jupiter
1. Install jupiter using pip: `install -U jupyter`
2. Install notebook using pip: `pip install -U notebook`
### VSCode 
1. Install the Azure Machine Learning extension for Visual Studio Code, see [Azure Machine Learning](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.vscode-ai)
### Azure ML SDK
1. Open VSCode on your Repo path
2. Create a notebook named `mailbot-demo-01`
3. Add a python cell with the code below. You should expect the version as the output (e.g. `'1.4.0'`)
```
#%%
import azureml.core
azureml.core.VERSION
```

# Dataset preparation

