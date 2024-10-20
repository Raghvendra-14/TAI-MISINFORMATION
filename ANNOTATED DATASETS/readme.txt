For experiments involving LLMs - We have provided sentiment and emotion annotated datasets, 500 samples from each dataset were randomly selected, with the exception of the Politifact dataset, which contains 432 samples. It is important to note that all the samples in all the datasets are from misinformation (rumour) class.

We also provide the models we used for sentiment (VADER) and emotion (DistilRoberta-base) annotation.

Here's a revised version of the text to make it sound clearer and more polished:


Additionally, from the extensive set of experiments, we evaluated a combination of 4 different LLMs across 2 different prompt settings (few-shot and zero-shot) and with or without the inclusion of sentiments and emotions. This resulted in 16 combinations per dataset, and with 6 datasets, a total of 96 experimental configurations were tested. For each of these configurations, we provide at least one instance of each LLM with the varying prompt settings and sentiment & emotion conditions. These configurations are designed to be flexible, allowing for minimal modifications to adapt to any required experimental setup. 

We also provide original and corrupted SNOPES dataset on which we ran the second part of our experiment along with our iterative based corruption of news articles using GPT-3.5


