# Case Studies

* This repository showcases a collection of applied case studies in machine learning (ML) and deep learning (DL), categorized by task type — Classification, Regression, Time Series, Deep Learning, and Natural Language Processing (NLP). 
* Each notebook demonstrates real-world problem solving with preprocessing, modeling, evaluation, and insights.

📁 Repository Structure

```bash
Classification/
├── AdClickClassification.ipynb        # Predict whether a user will click an ad
├── LoanApprovalData.ipynb             # Predict loan approvals based on user info

Regression/
├── ZomatoRestaurantRating.ipynb       # Predict restaurant ratings using review data
├── BikeRentalDemandPrediction.ipynb   # Predict bike rental demand based on weather/season

Time Series/
├── SuperStores_Sales_Analysis.ipynb   # Analyze and forecast Superstore sales

DL/
├── Predicting old car prices.ipynb    # Predict used car prices using deep learning
├── Predicting Stocks LSTM.ipynb       # Stock price prediction with LSTM
├── ANNRegression.ipynb                # ANN for generic regression tasks
├── CNN_face_recognition.ipynb         # Face recognition using CNN

NLP/
├── SupportTicketClassification_TF-IDF.ipynb   # Classify IT support tickets using TF-IDF
├── Classify_Text_Word2Vec.ipynb               # Word2Vec-based text classification
├── Indigo_Tweets_Sentiment.ipynb              # Sentiment analysis on Indigo tweets
```

📊 Model Accuracy Summary

```bash
+--------------------------------------------------------+--------------------+--------------------------+
| Notebook                                               | Task Type          | Final Accuracy / Metric  |
+--------------------------------------------------------+-------------------=+--------------------------+
| AdClickClassification.ipynb                            | Classification     | Accuracy = 94%           |
| LoanApprovalData.ipynb                                 | Classification     | Accuracy = 78%           |
| ZomatoRestaurantRating.ipynb                           | Regression         | Accuracy = 92%           |
| BikeRentalDemandPrediction.ipynb                       | Regression         | Accuracy = 90%           |
| SuperStores_Sales_Analysis.ipynb                       | Time Series        | Accuracy = 80%           |
| Predicting old car prices.ipynb                        | DL Regression      | Accuracy = 91%           |
| Predicting Stocks LSTM.ipynb                           | Time Series DL     | --                       |
| ANNRegression.ipynb                                    | DL Regression      | Accuracy = 90%           |
| CNN_face_recognition.ipynb                             | DL Regression      | Accuracy = 80%           |
| SupportTicketClassification_TF-IDF.ipynb               | NLP Classification | Accuracy ≈ 69%           |
| Classify_Text_Word2Vec.ipynb                           | NLP Classification | --                       |
| Indigo_Tweets_Sentiment.ipynb                          | NLP Sentiment      | F1 Score = 99%           |
+--------------------------------------------------------+--------------------+--------------------------+
```

🛠️ Requirements

* Python ≥ 3.8
* Jupyter Notebook
* pandas, numpy, matplotlib, seaborn, scikit-learn
* TensorFlow or PyTorch (for DL models)
* statsmodels (for time series)
* nltk, gensim, spaCy (for NLP tasks)


📈 How to Use

Clone the repository:

```bash
git clone https://github.com/anish3565/Case_Studies.git
cd Case_Studies
jupyter notebook
```

🧠 Author

> 🌟 **Star this repo** if you find it helpful.
> ✉️ [Let’s connect on LinkedIn](https://www.linkedin.com/in/anishnsut) for collaborations!
