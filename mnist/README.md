SDK-Example testing

Create a Code Repo: sdk-mnist
Create a Dataset Repo : sdk-mnist
Create a model Repo : sdk-mnist
Run the all cells of pipeline.ipynb file, it will create a pipeline with 2 stages i.e. training and serving.
Dkube training run will be created and the output is a sdk-mnist model
Go to sdk-mnist model and create test inference, replace transformer code as mnist/transformer.py and click on submit.
Go to https://<URL>:32222/inference
- Copy the model serving URL from the test inference tab.
- Copy the auth token from developer settings
- Select model type mnist
- Upload the digit image and click on predict
