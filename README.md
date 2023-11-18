<h1 align="center">
  Instagram comment classification thesis based on sentiment analysis 2023
</h1>

<p align="center">This is a study on how to classify the polarity of offensive comments on social networks, specifically on Instagram and directed at professional footballers.</p>

# Abstract
Currently, multiple machine learning models have been implemented for sentiment 
analysis that have the ability to classify text according to whether it is positive or 
negative, both individual words and complex sentences. However, the models with the 
highest hit rates have required high computational power to classify the text in question 
and also to be constantly updated with more examples.

In this case, the aim is to classify the polarity of offensive comments on social networks, 
specifically on Instagram and directed towards professional footballers.

Therefore, the objectives of this study have been defined firstly as the autonomous 
collection of data and the creation of a dataset to then train models. 
Following this thread, the next objectives are to investigate the different 
methodologies, technologies and models of the Python machine learning library, scikitlearn. Finally, after making a comparison between the 5 selected models, one of these 
models will be chosen to determine the polarity of the comments previously extracted 
by sentiment classification (“sentiment analysis”).

Despite the low level of personal knowledge available in the field of Natural Language 
Processing at the beginning, and the lack of computational capacity, the results of the 
model can be considered satisfactory, since a coherent classification based on a wellfounded justification is being obtained.

However, if the initial planning had been more accurate, the results could have been 
improved and if these data are intended to be used in another project, the model 
should be trained on a machine with higher computational capacity by which the model 
can be trained for a longer time with more advanced methods, such as some of those 
that are nowadays considered as part of the state of the art in this field.

## ⚡️ Quick start

First, we need to [download](https://www.python.org/downloads/) python `3.10.0` or higher is required, and preferably a python3-venv enviroment to install all the required packages.
This project has been developed using Anaconda environment (`23.3.1`) that´s why all the implementation files are .ipynb.

> If you are using venv you can easily create a new enviroment with "python3 -m venv venv" (Inside project's folder). <br>
> Activate the python3-venv with "source venv/bin/activate"

Once you have your enviroment setted up and ready to work with python you need to install the requirements that can be found on each of the different folders:

```bash
pip install -r ???_requirements.txt
```

## ⚙️ File Structure

### `/chromedriver_win32/chromedriver`

Chromedriver used together with selenium for web scrapping.

### `/InstagramScraping/instagram_api_comments_requirements`

The web scrapping notebook.

### `/CleanTranslateDataset/clean_translate_dataset.ipynb`

Here the initial dataset is translated.

### `/PredictCleanDataset/predict-dataset.ipynb`

Predict a dataset using a sklearn model.

### `/BertStuff/BERT-fine-tuning-and-evaluation.ipynb`

Just a simple study including results of the BERT model.

### `/SentimentAnalysis/`

A Jupyter Notebook used for all the models evaluations.
