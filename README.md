MLOPS Tutorials :


Deploy ML flask App in : 
	- AWS Fargate ===>  Tutorial already done ✅
	- GCP ===> Tutorial already done ✅
	- Azure Cloud ===> Tutorial already done ✅


Build, train and deploy models in AWS Sagemaker ===> covered today 🏃

Build Gradio app 

Build Gradio app and deploy in Hugging Face

Build Streamlit app

Build Streamlit app and deploy in Render hosting solution


ML Pipelines :
	- ZenML
	- MLFlow
	- KubeFlow
	- DVC
	- Pycaret




# Build, train and deploy models in AWS Sagemaker

Create an AWS Account or login if already created
search SageMaker
Clic on Studio
Clic on JupyterLab
Create JupyterLab space
For Name, specify the name of the space.
Choose Create space.
Choose Run space.
Choose Open JupyterLab.

Cliquer sur Terminal pour configurer l'environnement virtuel comme suit  :
	conda init
	conda create -n pycaretenv python=3.8
	conda activate pycaretenv
	pip install pycaret
	pip install ipykernel
	python -m ipykernel install --user --name pycaretenv --display-name "pycaretenvkernel"
	lancer jupyter depuis batch
	jupyter notebook


See test-sgm.ipynb

