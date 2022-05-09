# Natural Language Interface

This is the repository for Natural Language Inference project trained on snli dataset.

## Usage

Install conda client by following: https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html

### Install conda environment by running:
	conda env create --name NLIEnv --file=environments.yml

### Activate the conda environment by:
	conda activate NLIEnv


### Get the dataset from:
	https://drive.google.com/drive/folders/1vTtFEBvweUkSfH1pVe-mRbNTBmNFiPP4

### To preprocess the dataset, run:
	jupyter notebook NLI_Preprocessing.ipynb

### To train the model, run:
	jupyter notebook NLI_Training.ipynb

### To test the model, run:
	jupyter notebook NLI_Testing.ipynb

### Trained models:
	You can get the trained models from: https://drive.google.com/drive/folders/1LuGqDWmZlDWOBTc7U_nzBITxEGorpNFs

	latest_10000 is the model saved after every 10000 iterations on minibatches to give us a checkpoint in case of failure

	final_model is the final model saved after completing the training loop