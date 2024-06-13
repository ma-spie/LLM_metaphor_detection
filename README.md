#  LLM_metaphor_detection
This repository contains the materials for the paper ["Literary Metaphor Detection with LLM Fine-Tuning and Few-Shot Learning"](/Literary_Metaphor_Detection_Spielberg.pdf). 

## Project description

The paper explores the task of metaphor detection using Large Language Models (LLMs) from a Digital Humanities perspective, focusing on the detection of literary metaphors.
For this task, the Transformer-based model DisitlBERT and the Sentence Transformer-based model all-MiniLM-L6-v2 (using the SetFit framework) are fine-tuned on four datasets. 
The results suggest significant performance improvements for fine-tuning over baseline methods and for SetFit over traditional fine-tuning. However, since this improvement was not observed for all datasets, it is challenging to formulate generalised statements on the superiority of fine-tuning over traditional machine learning approaches for the MD task.

## Used datasets
The datasets for this project can either be found in the folder [raw_datasets](raw_datasets/) or downloaded from the links below:
1. [PoFo dataset](https://www.site.uottawa.ca/~diana/resources/metaphor/type1_metaphor_annotated.txt) by Kesarwani et al.
2. [TroFi dataset](https://github.com/YU-NLPLab/DeepMet/blob/master/data/TroFi/TroFi_formatted_all3737.csv) by Birke and Sarkar.
3. [MOH dataset](https://github.com/YU-NLPLab/DeepMet/blob/master/data/MOH-X/MOH-X_formatted_svo_cleaned.csv) by Mohammad et al.

## code
The [code](code/) folder contains notebooks for preprocessing, fine-tuning Transformers and SetFit and evaluation. The notebooks provide detailed explanations and instructions on the inputs and outputs for this project.

## fine-tuned models
The resulting fine-tuned models are publicly available on [Zenodo](https://doi.org/10.5281/zenodo.11624278).
