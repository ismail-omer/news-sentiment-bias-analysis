📰 News Bias Detector using NLP & Sentiment Analysis
📌 Overview

This project automates the detection of bias in news articles using Natural Language Processing (NLP) and sentiment analysis. It leverages multiple datasets and cutting-edge models to identify and quantify bias, sentiment polarity, and emotional tone in digital news content.

✨ Features

📊 Data Collection: Sources include Kaggle datasets and NewsAPI

🧹 Preprocessing: Text cleaning, tokenization, lemmatization

😀 Sentiment Analysis: Implemented with VADER and TextBlob

⚖️ Bias Detection: Rule-based + machine learning approaches

📈 Visualization: Interactive plots with Matplotlib & Seaborn

🧩 Modular Codebase: Reproducible, extensible, and scalable

📂 Project Structure
news-bias-detector-nlp/
├── data/
│   ├── raw/          # Original datasets
│   └── processed/    # Cleaned & preprocessed datasets
├── notebooks/        # Jupyter notebooks (experiments & analysis)
├── scripts/          # Reusable scripts for preprocessing, training, etc.
├── results/          # Generated results, reports & visualizations
├── requirements.txt  # Python dependencies
├── README.md         # Project documentation
├── LICENSE           # License file

⚙️ Installation

Clone the repository and install dependencies:
git clone https://github.com/ismail-omer/news-sentiment-bias-analysis.git
cd news-sentiment-bias-analysis
pip install -r requirements.txt

🚀 Usage

Explore the step-by-step implementation via Jupyter notebooks in /notebooks/:

Data loading & exploration

Preprocessing & feature engineering

Sentiment & bias detection models

Visualization & reporting

📑 Datasets

Raw datasets are stored in /data/raw/

Processed datasets are stored in /data/processed/

See data_description.md for dataset details

📊 Results

Generated results, metrics, and visualizations are saved in /results/.

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a pull request or submit an issue to improve this project.

📜 License

This project is licensed under the MIT License.

📚 References

Kaggle: Media bias datasets

NewsAPI documentation

Research papers on media bias detection & sentiment analysis
