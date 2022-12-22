<h1 align='center'>TEDTalks_Views_Prediction_Regression</h1>
<img align='center' height=400 src='https://media.giphy.com/media/eHR8ZtcloaFheQpKKk/giphy.gif'>
<h2> Problem Statement:</h2>

TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000 TED talks including transcripts in many languages
Founded in 1984 by Richard Salman as a nonprofit organization that aimed at bringing experts from the fields of Technology, Entertainment, and Design together.
TED Conferences have gone on to become the Mecca of ideas from virtually all walks of life. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates.

## Objective: 
To build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.


## Dataset Information

* Number of observations: 4,005
* Number of features: 19

## Features information:
The dataset contains features like:


* talk_id: Talk identification number provided by TED
* title: Title of the talk
* speaker_1: First speaker in TED's speaker list
* all_speakers: Speakers in the talk
* occupations: Occupations of the speakers
* about_speakers: Blurb about each speaker
* recorded_date: Date the talk was recorded
* published_date: Date the talk was published to TED.com
* event: Event or medium in which the talk was given
* native_lang: Language the talk was given in
* available_lang: All available languages (lang_code) for a talk
* comments: Count of comments
* duration: Duration in seconds
* topics: Related tags or topics for the talk
* related_talks: Related talks (key='talk_id',value='title')
* url: URL of the talk
* description: Description of the talk
* transcript: Full transcript of the talk

## Target Variable
* 'views': Count of views
<h2>Conclusion</h2>
The main objective was to build a predictive model, which could help in
predicting the views of the videos uploaded on the TEDx website.
Performed Exploratory data analysis on various features, then carried out feature
engineering and encoding of categorical columns, handled missing values in the
dataset then carried out feature selection and build various models.


Following models have been used:

* Linear Regression
* Random Forest Regressor

Evaluated these models on various metrics like MSE, RMSE, MAE ,R2 score.
Finally selected the best model out of these two.
After evaluating the performance of all the models, the best model is Random
Forest Regressor.
