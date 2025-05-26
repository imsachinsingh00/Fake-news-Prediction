# Fake News Prediction

This project implements a machine learning model to detect whether a news article is fake or real using natural language processing techniques.

## 📁 Project Structure

- `fake_news_prediction.ipynb`: Main notebook to clean, vectorize, train, and test the model.
- `README.md`: Documentation file.

## 📰 Dataset

This project uses a dataset of real and fake news articles. You can download a suitable dataset from:
- [Fake and real news dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)

Dataset should include columns like `title`, `text`, and `label`.

## ⚙️ Requirements

- Python 3.x
- pandas
- numpy
- sklearn
- matplotlib
- seaborn

Install with:
```bash
pip install -r requirements.txt
```

## 🧠 Techniques Used

- Text preprocessing
- CountVectorizer and TF-IDF
- Multinomial Naive Bayes classifier
- Train/Test split
- Evaluation metrics: accuracy, confusion matrix, classification report

## 🚀 How to Run

1. Download the dataset and place it in the project folder.
2. Open `fake_news_prediction.ipynb` in Jupyter.
3. Run all cells to train and evaluate the model.

## 📈 Sample Output

- Accuracy: ~95%
- Real-time prediction on custom input possible after model training.

## 📄 License

MIT License.
