# DailyShot-Indicator-OpenAI

## Overview
This project involves classifying the sentiment of financial equity-related snippets from articles by a news provider called DailyShot, and validated the sentiment against historical S&P 500 returns. It leverages OpenAI's GPT models and the FinancialBERT model for sentiment classification.

## Installation

### Prerequisites
- Python 3.10+
- An OpenAI API key

### Setting Up the Environment
1. **Clone the repository:**
   ```bash
   git clone https://github.com/liambeckman199/DailyShot-Indicator-OpenAI
   cd DailyShot-Indicator-OpenAI
   
### Install required packages

```bash
pip install -r requirements.txt
```

### OpenAI API Key
You need an OpenAI API key to run this project. Obtain it from [OpenAI](https://openai.com/).

Set the API key as an environment variable:

```bash
export OPENAI_API_KEY='your-api-key'
```

## Running the Jupyter Notebook
Launch Jupyter Notebook in the project directory and open the .ipynb file:

```bash
jupyter notebook
```

### Usage
The main notebook DailyShot Indicator-OpenAI.ipynb contains all the code and documentation to run the sentiment analysis models.
