# w266-project

## Abstract
Offensive language detection and other classification tasks often rely on large and well-labeled datasets. Low Resource Languages are languages for which large datasets may not exist or which may have incomplete or noisy datasets to train classification or other NLP tasks. In this project, we use pre-trained multilingual transformer models, mBERT and XLM-R, and a dataset in Amharic, a language spoken by around 50 million people in Ethiopia. In this work, we explore several techniques for utilizing and evaluating transfer learning and data-augmentation to increase performance in classifying social media posts as offensive or not in a Low Resource Language setting. The primary contributions we present in our paper are a data augmentation process and baselines that can provide the foundation for future work for researchers with the proper Amharic language background.


## Navigating the Files in this repository

|File | Description |
|:----|:------------|
| [`Amharic-Analysis.ipynb`](https://github.com/jcweaver/w266-project/blob/main/Amharic-Analysis.ipynb) | Analysis notebook used to identify the most common words in correctly & incorrectly identified comments. |
| [`EDA.ipynb`](https://github.com/jcweaver/w266-project/blob/main/EDA.ipynb) | A notebook used to read in Amharic & OLID datasets and do some initial EDA. |
| [`Error-Analysis.ipynb`](https://github.com/jcweaver/w266-project/blob/main/Error-Analysis.ipynb) | Analysis notebook used to explore the unique tokens detected in [`Amharic-Analysis.ipynb`](https://github.com/jcweaver/w266-project/blob/main/Amharic-Analysis.ipynb) and explore incorrect predicted comments. |
| [`lstm_baseline.ipynb`](https://github.com/jcweaver/w266-project/blob/main/lstm_baseline.ipynb) | LSTM Baseline Model |
| [`mBERT_pytorch.ipynb`](https://github.com/jcweaver/w266-project/blob/main/mBERT_pytorch.ipynb) | mBERT Model used on different sets of data. See comments. |
| [`data/`](https://github.com/jcweaver/w266-project/tree/main/data) | Data input and prediction files used in the models and analysis notebooks |
| [`XLMR-Amharic-Mono-Reserved.ipynb`](https://github.com/jcweaver/w266-project/blob/main/XLMR-Amharic-Mono-Reserved.ipynb) | |
| [`XLMR-Amharic-Mono.ipynb`](https://github.com/jcweaver/w266-project/blob/main/XLMR-Amharic-Mono.ipynb) | |
| [`XLMR-Amharic-Plus.ipynb`](https://github.com/jcweaver/w266-project/blob/main/XLMR-Amharic-Plus.ipynb) | XLMR run on Amharic + OLID data |
| [`XLMR-Amharic-Test-Reserved.ipynb`](https://github.com/jcweaver/w266-project/blob/main/XLMR-Amharic-Test-Reserved.ipynb) | |
| [`XLMR-Amharic.ipynb`](https://github.com/jcweaver/w266-project/blob/main/XLMR-Amharic.ipynb) | XLMR run on just Amharic |
| [`LMR_Fine_Tune_With_Articles.ipynb`](https://github.com/jcweaver/w266-project/blob/main/XLMR_Fine_Tune_With_Articles.ipynb) | XLMR finetuned on Amharic news |

