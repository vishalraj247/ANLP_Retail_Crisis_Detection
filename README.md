# Intelligent Crisis Detection and Response for Retail Brands

## Table of Contents
1. [Project Overview](#Project-Overview)
2. [Installation](#Installation)
3. [Usage](#Usage)
4. [Contributing](#Contributing)
5. [Data](#Data)
6. [Results](#Results)
7. [License](#License)

## Project Overview
The goal of this project is to build an NLP system capable of automatically identifying potential crises from articles, social media posts, and tweets, and generating appropriate responses to maintain the reputation of retail brands, with a focus on Amazon. 

## Installation
```bash
git clone https://github.com/vishalraj247/ANLP_Retail_Crisis_Detection.git
cd ANLP_Retail_Crisis_Detection
pip install -r requirements.txt
```
## Usage
1. Use web-scraping to gather data on Amazon-related articles and reviews.
2. Run `preprocessing section` to clean the scraped data and generate feature words.
3. Implement topic modeling.
4. For sentiment analysis on the processed data, run `sentiment_analysis section`.
5. Generate crisis topics using GPT-3.
6. Run `response_generation section` to create intelligent responses to crises using GPT-2 and GPT-3.
7. Evaluate the models using `model_evaluation section`.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Data
Data for this project was collected through web scraping of Amazon related articles from the Retail Dive website and customer reviews from www.consumeraffairs.com. Twitter data was collected using the MAXQDA software.

## Results
The system successfully identified crisis-related content within Amazon-related articles, reviews, and tweets. Using the GPT-3 API, it was able to generate relevant and impactful responses to the identified crises that were coherent, nuanced, and contextually tailored. The results demonstrate the considerable potential of NLP and AI technologies like GPT-3 in automating and enhancing the process of crisis detection and response for retail brands.

## License
[MIT](https://choosealicense.com/licenses/mit/)
