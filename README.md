# Data Science Salary and Sentiment Analysis Project

### Overview

This project leverages 2023 Reddit r/datascience data to analyze and categorize salaries of Data Scientists based on their job positions. In addition to salary analysis, the project performs sentiment analysis on the replies to the comments, providing insights into the community's sentiments towards various job roles and salaries.

### Features

**Salary Analysis:** Extract and format data from Reddit comments to categorize Data Scientist salaries based on job positions.

**Sentiment Analysis:**

- VADER Sentiment Analysis: Utilizes SentimentIntensityAnalyzer to classify replies as Positive, Neutral, or Negative.

- HuggingFace Transformer: Implements advanced sentiment analysis using a HuggingFace transformer model to further classify sentiments as Positive or Negative.
### Data Source

The dataset is scraped from the 2023 Reddit r/datascience subreddit, specifically from discussions related to job positions and salaries.

### Results

The project provides a comprehensive view of Data Scientist salaries across various job positions, along with an analysis of how these salaries are perceived by the community. The sentiment analysis offers a deeper understanding of the sentiments associated with different salary ranges and job titles.

### Future Work

Expand the dataset to include other subreddits or platforms for a broader analysis.
Improve the sentiment analysis model with additional training and fine-tuning on relevant datasets.
Incorporate geographical data to analyze salary variations by location.

### Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments

The Reddit r/datascience community for providing valuable data and discussions.
The open-source community for providing tools like VADER and HuggingFace for sentiment analysis.
