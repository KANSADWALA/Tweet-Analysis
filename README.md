# 📊 Tweet Analysis

## Overview
This project involves analyzing a dataset of 1.6 million tweets to extract meaningful insights through various analyses. The key objective is to perform sentiment analysis on the tweets and explore trends over time, user activity, and other metrics that can help understand the dynamics of the data. Advanced natural language processing techniques, along with data visualization, are employed to achieve this.

## Features

<ul>
  <li><strong>Sentiment Analysis:</strong> Categorizes tweets into positive, negative, or neutral sentiments.</li>
  
  <li><strong>Sentiment Trends Over Time:</strong> Analyzes how sentiments evolve over a specific period.</li>
  
  <li><strong>Tweet Volume Patterns:</strong> Explores tweet volume across different time frames to identify peaks and patterns.</li>
  
  <li><strong>Tweet Activity Over Time:</strong> Tracks the activity levels of tweets over time, helping to identify trends in user engagement.
</li>

  <li><strong>Total User Count:</strong> Provides the total number of unique users in the dataset.</li>
  
  <li><strong>Top 10 Most Active Users:</strong> Identifies and lists the top 10 users with the highest tweet counts.</li>
</ul>

## Technologies Used

<ul>
  <li><strong>Programming Languages:</strong> Python</li>
  
  <li><strong>Libraries:</strong> 
  <ul> 
    <li><strong>NumPy</strong> for numerical operations.</li>
    <li><strong>Pandas</strong> for data manipulation.</li>
    <li><strong>Matplotlib & Seaborn:</strong> Employed for data visualization.</li>
    <li>
      <strong>Scikit-learn</strong>  Used for machine learning tasks like feature extraction and dimensionality reduction.
             <ul><li><strong>Latent Dirichlet Allocation (LDA):</strong> For topic modeling to identify patterns in text data.
                </li>
             </ul>
    </li>
  </ul>
  </li>
  
  <li><strong>Regular Expressions (re):</strong> For text preprocessing and pattern matching.</li>
  
  <li><strong>NLTK (Natural Language Toolkit):</strong> Natural language processing.</li>
  
  <li><strong>Transformers (Hugging Face):</strong> Specifically, the `AutoModelForSequenceClassification` and `AutoTokenizer` were used for sentiment analysis with transformer models like RoBERTa.</li>
  


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
    <li>Download the dataset from Kaggle: <a href="https://www.kaggle.com/datasets/kazanova/sentiment140" >1.6 Million Tweets Dataset</a>.
    </li>
    <li>Extract the dataset and place it in the <code>data/</code> directory inside the project folder.</li>
</ol>

<h3>Running the Project</h3>
<p>Once everything is set up, you can run the analysis by executing the following command:</p>
<pre><code class="bash">
tweet analysis.ipynb
</code></pre>


</body>
</html>


## Project Structure

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<p>The directory structure of the project is as follows:</p>

<pre><code class="bash">
tweet-analysis/
│
├── data/
|   ├── kaggle.json
│   ├── training.1600000.processed.noemoticon.csv   # The Kaggle dataset of 1.6 million tweets
│                                                   
│
├── notebooks/
│   └── tweet_analysis.ipynb                        # Jupyter Notebook for sentiment analysis and other analyses
│ 
├── requirements.txt                                # List of dependencies
│
└── README.md                                       # Project documentation

</code></pre>

</body>
</html>



## Challenges faced

<b>Time Complexity in Sentiment Analysis:</b> The sentiment analysis using the roBERTa model was time-consuming due to the large dataset. This was addressed by optimizing the data pipeline and using batch processing.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.


## Contact
For any questions or suggestions, please open an issue or contact me at <a href="mailto:shubhamkansadwala@gmail.com">shubhamkansadwala@gmail.com</a>
.
<hr></hr>
