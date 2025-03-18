# PYPI PYTHON STUDY RESOURCES
This is a simple idea of grouping my notes and study material in a single space, 
thus creating a PyPi module where everyone can access these.
Also, the print-text is colored!

## Installation and Use
Install the module from PIP:
```bash
pip install gobbezlearningtoolbox
```

Check all the materials in the module:
```bash
from gobbezlearningtoolbox.listall import ListAll
print(ListAll())
```

Use the material you want to study and find all the contents (example code):
```bash
from gobbezlearningtoolbox.datascience import DataScience

ds = DataScience()
print(ds.help())
```

Pick a content and start studying (example code):
```bash
from gobbezlearningtoolbox.datascience import DataScience

ds = DataScience()
print(ds.machinelearning())
```

## List of materials:
#### DataScience: 
Methods and most common functions for Data Science, DataFrame manipulation and Machine Learning.
* imports_dataframe():
* imports_machinelearning(): 

* eda(): 
* operations():


#### DeepLearning:
Most common Keras Deep Learning models.
* imports_regression(): Most used imports for Keras Deep Learning - Regression
* imports_classifier(): Most used import for Keras Deep Learning - Classifier

* sequential(): Simple ready-to-go guide for a sequential Deep Learning model using Keras  
* image_classifier(): Simple model to classify images using CNN

* dropout(): Explain how to set a simple DropOut
* learning_rate_scheduler(): Explain how to modify learning rate based on epochs
* mixed_precision(): Explain how to setup a mixed_precision training
* gradient_accumulation(): Explain how to use gradient accolumation to increase batch size

* compile(): Explain how to compile a model
* train(): Explain how to train a model
* train_with_gradient_accumulation(): Explain advanced techniques for training a model
* predict_regression(): Explain how to make regression predictions with the model
* predict_classification(): Explain how to make classification predictions with the model
* evaluate(): Explain how to evaluate the model

* plot(): Explain how to plot results of the model

#### TelegramBot:
Simple quick-start guide for the python-telegram-bot module to create your own Telegram Bot.
* imports(): Find the most common imports to start 

* quick_start(): Quick setup explanations


## Contribute
You can contribute to the GitHub Repository or use it locally:
```bash
git clone https://github.com/gobbez/gobbezlearningtoolbox.git
```

## Notes
Please note that this module isn't complete, and it only gives a basic entry-level to start.
For more information contact me.
You can find the PyPi module here: https://pypi.org/project/gobbezlearningtoolbox


## Updates
* added telegrambot (18/03/2025)
* added listall (15/03/2025)
* added deeplearning (15/03/2025)
* added datascience (15/03/2025)

