# UC Berekely Data Analytics Bootcamp Final Project August 2019

# Neural Networks, ML, and NLP for hate speech classification

Sentiment analysis of streaming data is quickly approaching ubiquity. From the nonprofit sector to business to government agencies, virtually any manner of organization stands to benefit from performing some sort of “opinion mining” on available data. One common use case is the analysis of data from social media activity to gain a sense of the “feeling” that underlies posts and comments.

In light of the recent social climate, and the growing link between hateful rhetoric becoming hateful actions, we have chosen to use our skills as Data Analysts to develop a tool that can query a data source and classify speech in text as either 'hateful', 'offensive', or 'neither hateful nor offensive'.

Long Short-Term Memory classification model to classifies text as either ‘hateful’, ‘offensive’, or ‘neither hateful nor offensive’. 

### Repo Structure
Live Application - https://www.erasehateapp.com

[Deployed Application Components](https://github.com/nickmccarty/Twitter-Sentiment-Analysis/tree/master/Omari/Version3.0_11_6_2019 'Live App')
The complete deployed application and its components can be found here.

- Folder: Main - The web facing front end. An AWS deployed front-end. Responsible for executing/routing users queries.  
- Folder: ModelServer - A dedicated AWS instance used only for serving predictions from the LSTM model.
- Folder: Vote_Retrain - Scripts that control the database functions, and model retraining procedure

**A library for prior versions is contained here** [Version Repo](https://github.com/oblockton/Erase-Hate-Versioning 'Version Repo')

[LSTM Model Building](https://github.com/nickmccarty/Twitter-Sentiment-Analysis/tree/master/FINAL/LSTM 'LSTM Model Building')

[API Repo & Docs](https://github.com/oblockton/Erase_Hate_Python_Library 'API Repo & Docs')
PyPi Module https://pypi.org/search/?q=erasehate


Training data from previous on work done by Davidson, et al. (2017), as detailed in their [paper](https://arxiv.org/abs/1703.04009).

Our presentation of our findings can be found [here](https://drive.google.com/file/d/1Q8i7kgMXVrcf7ohsbQ5v3Vr6dU0MOkvn/view?usp=drivesdk).
