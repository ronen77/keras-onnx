
Final project

Directory Includes:
1. models         - both mode_1 (i.e. simple) and model_2 (i.e. more complicated)
2. data_v1        - dedicated for model_1 intermediate files
3. data_v2        - dedicated for model_2 intermediate files
4. dvc_repository - A local repository, to save the "big" data (i.e. model_1 & model_2)
5. raw_data       - holds all available data (train, validation, test) @ each month
6. mlflow         - some pictures for mlflow
6. html           - html file for the main train notebook

Git Hub Repository:
https://github.com/ronen77/keras-onnx


Q: How to run the mlflow?
A: 1. open anaconda command prompt to the main direcory (i.e. C:\working\gitos\keras-onnx)
      execute: jupyter notebook, and oprn the 'train.ipynb'
   2. open addition anaconda command prompt to the 'data_v1' folder (i.e. C:\working\gitos\keras-onnx\data_v1)
      execute: mlflow ui (INFO:waitress:Serving on http://127.0.0.1:5000)
   3. open browser and observe the accuracy graph   


Q: How to create .env?
A: python3 -m venv .env
   source .env/bin/activate
   pip install -r requirements.txt

Advanced (future) Topics:
1. create virtual environment
2. create local key to actualy connect to S3 for saving the "big" data
3. update %accuracy in the markdown comments, automatically
4  pre-install all modules in 'requirements.txt' file 
5. commit & push all changes to github

 







