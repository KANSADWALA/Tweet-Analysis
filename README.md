# Tweet-Analysis

## Overview
This project involves analyzing a dataset of 1.6 million tweets to extract meaningful insights through various analyses. The key objective is to perform sentiment analysis on the tweets and explore trends over time, user activity, and other metrics that can help understand the dynamics of the data. Advanced natural language processing techniques, along with data visualization, are employed to achieve this.

## Features

<ul>
  <li><b>Sentiment Analysis:</b> Categorizes tweets into positive, negative, or neutral sentiments.</li>
  
  <li><b>Sentiment Trends Over Time:</b> Analyzes how sentiments evolve over a specific period.</li>
  
  <li><b>Tweet Volume Patterns:</b> Explores tweet volume across different time frames to identify peaks and patterns.</li>
  
  <li><b>Tweet Activity Over Time:</b> Tracks the activity levels of tweets over time, helping to identify trends in user engagement.
</li>

  <li><b>Total User Count:</b> Provides the total number of unique users in the dataset.</li>
  
  <li><b>Top 10 Most Active Users:</b> Identifies and lists the top 10 users with the highest tweet counts.</li>
</ul>

## Technologies Used

<ul>
  
  <li><b>NumPy:</b> For numerical computations.</li>
  
  <li><b>Pandas:</b> Utilized for data manipulation and analysis.</li>
  
  <li><b>Matplotlib & Seaborn:</b> Employed for data visualization.</li>

  <li><b>Scikit-learn:</b> Used for machine learning tasks like feature extraction and dimensionality reduction.
</li>

  <li><b>Latent Dirichlet Allocation (LDA):</b> For topic modeling to identify patterns in text data.
  </li>

  <li><b>Regular Expressions (re):</b> For text preprocessing and pattern matching.</li>
  
  <li><b>NLTK (Natural Language Toolkit):</b> Natural language processing.</li>
  
  <li><b>Transformers (Hugging Face):</b> Specifically, the `AutoModelForSequenceClassification` and `AutoTokenizer` were used for sentiment analysis with transformer models like RoBERTa.</li>
  
  <li><b>Jupyter Notebook:</b> Used for experimentation and development.</li>
</ul>


## Getting Started

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h3>Prerequisites</h3>
<p>Ensure that you have the following installed on your local machine:</p>
<ul>
    <li><strong>Python 3.8+</strong>: The project is built using Python. You can download Python from <a href="https://www.python.org/downloads/">python.org</a>.</li>
    <li><strong>pip</strong>: Python's package installer, which is typically included with Python installations.</li>
    <li><strong>Git</strong>: For cloning the repository.</li>
</ul>

<h3>Installation</h3>
<ol>
    <li><strong>Clone the Repository:</strong>
        <pre><code class="bash">
git clone https://github.com/yourusername/tweet-analysis.git
cd tweet-analysis
        </code></pre>
    </li>
    <li><strong>Create a Virtual Environment:</strong>
        <pre><code class="bash">
python3 -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
        </code></pre>
    </li>
    <li><strong>Install Required Packages:</strong>
        <pre><code class="bash">
pip install -r requirements.txt
        </code></pre>
    </li>
</ol>

<h3>Data Preparation</h3>
<p>The dataset used in this project is available on Kaggle. You need to download the dataset and place it in the appropriate directory:</p>
<ol>
    <li>Download the dataset from Kaggle: <a href="[https://www.kaggle.com/datasets/your-dataset-url](https://www.kaggle.com/datasets/kazanova/sentiment140)">1.6 Million Tweets Dataset</a>.</li>
    <li>Extract the dataset and place it in the <code>data/</code> directory inside the project folder.</li>
</ol>

<h3>Running the Project</h3>
<p>Once everything is set up, you can run the analysis by executing the following command:</p>
<pre><code class="bash">
tweet analysis.ipynb
</code></pre>

<h3>Accessing Results</h3>
<p>The results, including visualizations and summary statistics, will be saved in the <code>results/</code> directory. You can view these results by navigating to the directory and opening the corresponding files.</p>

</body>
</html>


## Project Structure

tweet-analysis/
│
├── data/
│   ├── training.1600000.processed.noemoticon.csv                 # The Kaggle dataset of 1.6 million tweets
│                                                                 # Preprocessed data after cleaning and analysis
│
├── notebooks/
│   └── tweet_analysis.ipynb                                      # Jupyter Notebook for sentiment analysis and other analyses
│ 
├── requirements.txt                                              # List of dependencies
│
└── README.md                                                     # Project documentation


## Challenges and Solutions

<b>Time Complexity in Sentiment Analysis:</b> The sentiment analysis using the roBERTa model was time-consuming due to the large dataset. This was addressed by optimizing the data pipeline and using batch processing.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.


## Contact
For any questions or suggestions, please open an issue or contact me at <a href="mailto:shubhamkansadwala@gmail.com">shubhamkansadwala@gmail.com</a>
.
<hr></hr>
