

## Steps

1. Create a env
2. Activate it
3. Create a jupyter env
4. Start jupityer

### Popular commands

```bash

# if jupyter is not installed
# brew install jupyter

#Step 1
python3 -m venv jenv
#second parameter the name of the engv


##Step 2
source jenv/bin/activate

#if you want to install required 
python3 -m pip install -r requirements.txt

#check env
which python3

#Step 3
pip install ipykernel

python -m ipykernel install --name=jpy-venv
# to deactive jupyter kernelspec uninstall jpy-venv

# Start Jupyter
jupyter notebook

```


## References

> https://learnpython.com/blog/python-requirements-file/

> https://realpython.com/python-virtual-environments-a-primer/




* [projects/](./projects)
  * [emotionsDataExploration/](./projects/emotionsDataExploration)
    * [Emotions.ipynb](./projects/emotionsDataExploration/Emotions.ipynb)
    * [text_emotion.csv](./projects/emotionsDataExploration/text_emotion.csv)
  * [emotionsImagePrediction/](./projects/emotionsImagePrediction)
    * [good-facial-expression-eda-cnn-with-youtube.ipynb](./projects/emotionsImagePrediction/good-facial-expression-eda-cnn-with-youtube.ipynb)
    * [good-facial-expression-eda-cnn.ipynb](./projects/emotionsImagePrediction/good-facial-expression-eda-cnn.ipynb)
  * [emotionsNLPPrediction/](./projects/emotionsNLPPrediction)
    * [BERTPytorch/](./projects/emotionsNLPPrediction/BERTPytorch)
      * [prettygood-classify-emotions-in-text-with-bert-pytorch.ipynb](./projects/emotionsNLPPrediction/BERTPytorch/prettygood-classify-emotions-in-text-with-bert-pytorch.ipynb)
    * [BERTTensorflowKeras/](./projects/emotionsNLPPrediction/BERTTensorflowKeras)
      * [good-emotion-detection-using-fine-tuned-bert-tf.ipynb](./projects/emotionsNLPPrediction/BERTTensorflowKeras/good-emotion-detection-using-fine-tuned-bert-tf.ipynb)
    * [BERTTensorflowKerasPredictYoutubeTranscriptedVideo/](./projects/emotionsNLPPrediction/BERTTensorflowKerasPredictYoutubeTranscriptedVideo)
    * [LSTM/](./projects/emotionsNLPPrediction/LSTM)
      * [emotion-analysis-and-prediction-using-lstm-93.ipynb](./projects/emotionsNLPPrediction/LSTM/emotion-analysis-and-prediction-using-lstm-93.ipynb)
  * [instagramETL/](./projects/instagramETL)
    * [InstagramETL.ipynb](./projects/instagramETL/InstagramETL.ipynb)
    * [instagram_profiles.csv](./projects/instagramETL/instagram_profiles.csv)
    * [readme.md](./projects/instagramETL/readme.md)
  * [netflix/](./projects/netflix)
    * [Netflix.ipynb](./projects/netflix/Netflix.ipynb)
    * [netflix_titles.csv](./projects/netflix/netflix_titles.csv)
    * [readme.md](./projects/netflix/readme.md)
  * [titanic/](./projects/titanic)
    * [Titanic.ipynb](./projects/titanic/Titanic.ipynb)
    * [gender_submission.csv](./projects/titanic/gender_submission.csv)
    * [readme.md](./projects/titanic/readme.md)
    * [submission.csv](./projects/titanic/submission.csv)
    * [test.csv](./projects/titanic/test.csv)
    * [train.csv](./projects/titanic/train.csv)
  * [twitterSentiment/](./projects/twitterSentiment)
    * [TwitterSentiment.ipynb](./projects/twitterSentiment/TwitterSentiment.ipynb)
    * [training.1600000.processed.noemoticon.csv](./projects/twitterSentiment/training.1600000.processed.noemoticon.csv)
  * [weatherPrediction/](./projects/weatherPrediction)
    * [WeatherPrediction.ipynb](./projects/weatherPrediction/WeatherPrediction.ipynb)* [projects/](./projects)

  * [emotionsDataExploration/](./projects/emotionsDataExploration)

    * [Emotions.ipynb](./projects/emotionsDataExploration/Emotions.ipynb)
    * [text_emotion.csv](./projects/emotionsDataExploration/text_emotion.csv)
  * [emotionsImagePrediction/](./projects/emotionsImagePrediction)
    * [good-facial-expression-eda-cnn-with-youtube.ipynb](./projects/emotionsImagePrediction/good-facial-expression-eda-cnn-with-youtube.ipynb)
    * [good-facial-expression-eda-cnn.ipynb](./projects/emotionsImagePrediction/good-facial-expression-eda-cnn.ipynb)
  * [emotionsNLPPrediction/](./projects/emotionsNLPPrediction)
    * [BERTPytorch/](./projects/emotionsNLPPrediction/BERTPytorch)
      * [prettygood-classify-emotions-in-text-with-bert-pytorch.ipynb](./projects/emotionsNLPPrediction/BERTPytorch/prettygood-classify-emotions-in-text-with-bert-pytorch.ipynb)
    * [BERTTensorflowKeras/](./projects/emotionsNLPPrediction/BERTTensorflowKeras)
      * [good-emotion-detection-using-fine-tuned-bert-tf.ipynb](./projects/emotionsNLPPrediction/BERTTensorflowKeras/good-emotion-detection-using-fine-tuned-bert-tf.ipynb)
    * [BERTTensorflowKerasPredictYoutubeTranscriptedVideo/](./projects/emotionsNLPPrediction/BERTTensorflowKerasPredictYoutubeTranscriptedVideo)
    * [LSTM/](./projects/emotionsNLPPrediction/LSTM)
      * [emotion-analysis-and-prediction-using-lstm-93.ipynb](./projects/emotionsNLPPrediction/LSTM/emotion-analysis-and-prediction-using-lstm-93.ipynb)
  * [instagramETL/](./projects/instagramETL)
    * [InstagramETL.ipynb](./projects/instagramETL/InstagramETL.ipynb)
    * [instagram_profiles.csv](./projects/instagramETL/instagram_profiles.csv)
    * [readme.md](./projects/instagramETL/readme.md)
  * [netflix/](./projects/netflix)

    * [Netflix.ipynb](./projects/netflix/Netflix.ipynb)
    * [netflix_titles.csv](./projects/netflix/netflix_titles.csv)
    * [readme.md](./projects/netflix/readme.md)
  * [titanic/](./projects/titanic)

    * [Titanic.ipynb](./projects/titanic/Titanic.ipynb)
    * [gender_submission.csv](./projects/titanic/gender_submission.csv)
    * [readme.md](./projects/titanic/readme.md)
    * [submission.csv](./projects/titanic/submission.csv)
    * [test.csv](./projects/titanic/test.csv)
    * [train.csv](./projects/titanic/train.csv)
  * [twitterSentiment/](./projects/twitterSentiment)

    * [TwitterSentiment.ipynb](./projects/twitterSentiment/TwitterSentiment.ipynb)
    * [training.1600000.processed.noemoticon.csv](./projects/twitterSentiment/training.1600000.processed.noemoticon.csv)
  * [weatherPrediction/](./projects/weatherPrediction)

    * [WeatherPrediction.ipynb](./projects/weatherPrediction/WeatherPrediction.ipynb)
