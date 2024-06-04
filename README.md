# Centralized and Federated Bert-Based Hate-Speech Recognition

## Abstract
_Content warning: This paper contains unfiltered content reported by Hate Speech Datasets that may be offensive to readers._

Hate speech recognition is a critical task for maintaining healthy online communities. This paper explores the efficacy of Federated Learning (FL) in enhancing hate speech detection models compared to traditional centralized approaches. We evaluate several state-of-the-art centralized models, including BERT-based models, Random Forests, Decision Trees, K-Nearest Neighbors (KNN), and Logistic Regression. We introduce their federated counterparts, facilitating distributed training across multiple devices while preserving data privacy. Our experimental results, benchmarked using F1 score and accuracy metrics, indicate that FL models outperform centralized models by a significant margin, achieving over $7\%$ higher accuracy. These findings underscore the potential of Federated Learning to improve the robustness and performance of hate speech recognition systems, paving the way for more secure and effective content moderation strategies.

## Files

## Getting Started

### Dataset
Large datasets (used in performance evaluation) can be downloaded from https://drive.google.com/drive/folders/1-7rT1GF8gT6ZlZI9k5hXINArWqTjDhXC?usp=sharing and placed into the `datasets` folder. 

In our code, 0 refers to non-hateful, and one refers to hateful tweets. 

There are three datasets there, and their information is summarized in the table below:


| Dataset |  Train Size (70%)  | Test Size (30%) | Prompt Column, Label Column |
|:-----:|:--------:|:------:|:------:| 
| Kaggle (1)   | 31962 | 17197 |  tweet,label |
| Kaggle (2)   |  111780  |   47905 | Text, oh_label |
| Davidson   | 3915 |    1678 | tweet, class |

**note:** The Davidson dataset has classes 0: hateful, 1 offensive, and 2 neither. We filter out offensive language rows and change their labels by mapping 0 to 1 and 2 to 0.


### Data Pre-Processing


### Datasets Visualization


### Evaluation




## Cite:
