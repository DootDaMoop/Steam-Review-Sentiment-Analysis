# Steam-Review-Sentiment-Analysis
This project is a sentiment analysis project that utilizes the [Steam Review](https://www.kaggle.com/datasets/andrewmvd/steam-reviews/data) dataset by [Larxel](https://www.kaggle.com/andrewmvd) on Kaggle. This program uses two approaches: Multinomial Naive Bayes Model from Scikit-Learning, and Neural Network Sequential Architecture from Tensorflow. This is mean't for usage for my class and may not be accessable to other users.

## Requirements
itcs-3156 kernal

## Installation
1. Clone the Repository:
```
git clone https://github.com/DootDaMoop/Steam-Review-Sentiment-Analysis.git
cd steam-review-sentiment-analysis
```
2. If using the kernal, open in anaconda and use JupyterLabs, JupyterNotebooks, or VSCode. Set your kernal and you may skip to step 5. If you don't have access to the kernal, skip to step 3.

3. Create your virtual environment
```
python -m venv venv
source venv/Scripts/activate # Windows
source venv/bin/activate # Mac or Linux
```

4. Install the requirements
```
pip install -r requirements.txt
```

5. Make sure you download the [Steam Review](https://www.kaggle.com/datasets/andrewmvd/steam-reviews/data) dataset and put in the main directory. Make sure you rename the dataseet to "SteamReviews.csv"

6. You may run the code with Run All or snippet by snippet. There may be additional pip installs within the .ipynb file.