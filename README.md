# AI vs Real Image Detector

## Dependencies

### Datasets to Download

The dataset for this program is found here:
https://www.kaggle.com/datasets/alessandrasala79/ai-vs-human-generated-dataset/data

#### What to Download

Under Data Explorer, download the following folders:

Training image dataset --> `train_data`

Testing image dataset --> `test_data_v2`

Under this repository, download the following files:

Project notebook --> `AI_vs_Real_Images.ipynb`

Training image CSV --> `train.csv`

Testing image CSV --> `test.csv`

#### Ensure all files are in the same directory

### Required Packages

To install necessary dependencies, input this command into your local terminal:

    pip install numpy tensorflow matplotlib pillow kagglehub[pandas-datasets]

### Python Requirement

Ensure your local python interpreter is version 3.10 by inputting this command into your local terminal:

    python -v

If your python version is not the correct version, certain dependencies may not function correctly. To 
modify your version, download python 3.10 here: https://www.python.org/downloads/release/python-3100/

Afterwards, setup your local interpreter with python 3.10, and ensure the previous dependencies are installed.


## Run the Program

After all dependencies are downloaded, the program is ready to run!

After training the model, the program will save the model as `discriminator_model.h5`. Our saved model is provided in the repository in case the training model may be too expensive to run.

