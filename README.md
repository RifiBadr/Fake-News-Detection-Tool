# Fake News Detection Tool

## Project Overview
The Fake News Detection Tool is designed to identify and classify news articles as real or fake. Utilizing advanced machine learning techniques, the tool processes and analyzes textual data to determine its veracity. The project leverages popular Python libraries and machine learning models, including Logistic Regression, Decision Tree, and Random Forest classifiers.

## Datasets Used
The project makes use of two public datasets:
- **FakeNewsNet (PolitiFact)**: Contains labeled news articles as real or fake.
- **LIAR Dataset**: Consists of short statements rated on a truthfulness scale, used for binary classification.
- Datasets can be downloaded from the [Fake News Inference Dataset](https://ieee-dataport.org/open-access/fnid-fake-news-inference-dataset) on IEEE Dataport.

## System Requirements
- **Operating System**: Compatible with Windows, macOS, and Linux.
- **Python Version**: Python 3.8 or later.

## Dependencies
Before running the project, install the required Python libraries using the following command:
```bash
pip install pandas numpy nltk scikit-learn matplotlib seaborn

## Additional Setup
Ensure you the necessary NLTK are downloaded :
import nltk
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')

## Usage

1. Clone the repository:
git clone https://github.com/RifiBadr/fake-news-detection-tool.git

2. Navigate to the project directory:
cd fake-news-detection-tool

3. Install required Python libraries (if not previously installed):
pip install pandas numpy nltk scikit-learn matplotlib seaborn

4. Execute the Jupyter Notebook:
python FakeNewsDetectionTool.ipynb



