# Lab-3-Classification-Transformer-Text-generation-

## Objective
The main objective of this project is to leverage PyTorch and build deep neural network architectures for Natural Language Processing (NLP) using Sequence Models. The project is divided into two parts: a text classification task and text generation using a transformer model.

## Part 1: Classification Task
### 1. Data Collection
- Utilized web scraping libraries (Scrapy / BeautifulSoup) to collect text data from various Arabic websites on a specific topic.
- website : 'https://akhbarak.net/blog/114808/%D8%A7%D8%B3%D8%A6%D9%84%D8%A9-%D8%AF%D9%8A%D9%86%D9%8A%D8%A9-%D8%A7%D8%B3%D9%84%D8%A7%D9%85%D9%8A%D8%A9-%D9%84%D9%84%D9%85%D8%B3%D8%A7%D8%A8%D9%82%D8%A7%D8%AA-%D8%B5%D8%B9%D8%A8%D8%A9-%D9%88%D8%B3/',

- Prepared the dataset with relevance scores for each text (ranging from 0 to 10) (view file : arabic_dataset).

### 2. Preprocessing NLP Pipeline
- Implemented a preprocessing pipeline involving tokenization, stemming, lemmatization, stop words removal, discretization, etc.

### 3. Model Training
- Trained models using RNN, Bidirectional RNN, GRU, and LSTM architectures.
- Tuned hyperparameters to optimize performance.

### 4. Evaluation
- Evaluated the language models using standard metrics and additional metrics such as the BLEU score.



## Part 2: Transformer (Text Generation)

1. **Transformer Setup:**
   - Installed `pytorch-transformers`.
   - Loaded the GPT-2 pre-trained model.

2. **Fine-Tuning:**
   - Fine-tuned the pre-trained GPT-2 model on a customized dataset.

3. **Text Generation:**
   - Generated new paragraphs based on given sentences.

## Getting Started

Follow the steps below to replicate the project on your local machine.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git

You can follow this tutorial :
https://gist.github.com/mf1024/3df214d2f17f3dcc56450ddf0d5a4cd7
