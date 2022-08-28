> University of Pisa, UNIPI \
> Academic year 2021/22 \
> Authors: [Irene Pisani](), [Alice Bergonzini](https://github.com/alicebergonzini) \
> September, 2022

# Human Language Technologies
###### Final project for HLT course (Prof. Giuseppe Attardi)


## Key Point Analysis: Key Point Matching and Key Point Generation with Pre-Trained Language Models
  
  * **Dataset:**                 [Official KPA-2021 dataset - ArgKP-2021](https://github.com/IBM/KPA_2021_shared_task)
  * **Key Point Matching:**      [`KPA_KeyPointMatching.ipynb`](Code/KPA_KeyPointMatching.ipynb)
  * **Key Point Generation:**    [`KPA_KeyPointGeneration.ipynb`](Code/KPA_KeyPointGeneration.ipynb)
  * **Report:**                  [KPA_report.pdf](KPA_report.pdf)


### Abstract
This work aims to describe simple approaches for solving *Key Point Matching* (KPM) and *Key Point Generation* (KPG) tracks proposed at **Argument Mining 2021** in the context of the shared task on *Quantitative Summarization* and *Key Point Analysis* (KPA). 
The presented methods rely on the fine-tuning of some state-of-the-art pre-trained language models both for KPM and KPG subtasks. 
Regarding the KPM task all the models explored were validated using the Hold-Out validation technique and their results were compared to analyze their effectiveness within the task. Leveraging **DeBERTa** pre-trained transformer, our best model yields to competitive performance since it achieved on the test set a **mAP Strict** and **mAP Relaxed** score of, respectively, **0,7035** and **0,8857**. 
For the KPG task, a simple baseline based on abstractive summarization approach was provided; our system takes advantage of the pre-trained **Google mT5** transformer to generate several key points that are finally properly selected.
