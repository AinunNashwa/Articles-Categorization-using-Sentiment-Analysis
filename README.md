 <a><img alt='tf' src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"></a>
 <a><img alt = 'image' src="https://img.shields.io/badge/Spyder%20Ide-FF0000?style=for-the-badge&logo=spyder%20ide&logoColor=white"></a>
 <a><img alt = 'image' src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"></a>
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Spyder](https://img.shields.io/badge/Spyder-838485?style=for-the-badge&logo=spyder%20ide&logoColor=maroon)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

# Articles Categorization using Sentiment Analysis

### Descriptions
1) The objectives of this project is to develop model that can filter the articles into different categories. 
2) Trained with over 2000 IMDB dataset to categorize into namely *Sport, Tech, Business, Entertainment and Politics*.
3) Contains 2,225 texts and 2,225 categories
4) Data contains anomalies such as numbers, unnecessary characters and spaces.
5) Methods used to train the model: `Word Embedding`,`LSTM`,`Bidirectional`, `Drop out`, `Dense`

### Results
`Model`

<img src="static/model.png" alt="model" style="width:300px;height:500px;">

`Classification_Report`

`Confusion_Matrix`

`Training Data`

`Tensor Board`

### Discussion
1) Model achieved approximately 93% accuracy
2) Recall and f1 score reports around 89% t0 90% accuracy
3) However the model starts to overfit after 4th epoch

*Suggestions to Improve the Performance of Model*

1) Apply `Early Stopping` to prevent overfitting
2) Increase `Droput rate` to control overfitting
3) Increase the model `complexity`: increase number of nodes and dense
4) Further improvement during preprocessing data is by applying : `Stemming`, `Lemmatization`, `Stopwords`
5) Approach with different architecture such as: `BERT Model`,`Transformer Model`,`GPT3`

### Credits
`You can load the dataset from here`
https://raw.githubusercontent.com/susanli2016/PyCon-Canada-2019-NLP-Tutorial/master/bbc-text.csv


