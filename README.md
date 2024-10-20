
# Repository Overview

This repository houses the data and code for the experiments detailed in the paper titled "Silver Lining in the Fake News Cloud: Can Large Language Models Help Detect Misinformation?" *Accepted in IEEE TAI (CURRENTLY IN EARLY ACCESS PHASE)*. It includes resources for experimenting with Large Language Models (LLMs) as follows:

## Datasets

- **Sentiment and Emotion Annotated Datasets**: We provide sentiment and emotion annotated datasets, with 500 samples randomly selected from each dataset, except the Politifact dataset, which includes 432 samples. All samples are classified under the misinformation (rumour) category.

## Models

- **Sentiment and Emotion Annotation Models**: Included are the models used for sentiment annotation (VADER) and emotion annotation (DistilRoberta-base).

## Experimental Configurations

- **LLM Experimentation**: We conducted a comprehensive evaluation involving 4 different LLMs across 2 prompt settings (few-shot and zero-shot), with and without sentiment and emotion annotations. This resulted in 16 combinations per dataset, totaling 96 experimental configurations across 6 datasets. For each configuration, we provide at least one instance of each LLM with the varied prompt settings and sentiment & emotion conditions. These configurations are designed for flexibility and can be easily adapted to different experimental setups.

## Additional Resources

- **SNOPES Dataset**: We offer both the original and corrupted versions of the SNOPES dataset, used in the second phase of our experiments. The corruption process was performed using GPT-3.5.

- **Linguistic Analysis Code**: Code for calculating linguistic aspects such as abstractness, concreteness, Named Entity Ratio, and readability scores is included.

- **ML Classifiers and BERT Embeddings**: The repository contains code for machine learning classifiers and BERT embeddings generation, as detailed in the paper's appendix. All datasets used are publicly available. Readers can download these datasets and select the first 1000 samples from each class (rumor/fake and non-rumor/real) for training the classifiers. For testing, please use the datasets provided in the annotated data section.

## please use below citation

```
@ARTICLE{10631663,
  author={Kumar, Raghvendra and Goddu, Bhargav and Saha, Sriparna and Jatowt, Adam},
  journal={IEEE Transactions on Artificial Intelligence}, 
  title={Silver Lining in the Fake News Cloud: Can Large Language Models Help Detect Misinformation?}, 
  year={2024},
  volume={},
  number={},
  pages={1-11},
  keywords={Fake news;Social networking (online);Large language models;Task analysis;Chatbots;Linguistics;Blogs;Fake News;Large Language Models (LLMs);Misinformation Detection;Prompting Techniques;Rumour News;Sentiment and Emotion},
  doi={10.1109/TAI.2024.3440248}}
```
