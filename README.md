# NLP Coursework

This README.txt file describes the content of the repository for the NLP Coursework produced by Alan Picucci, Ivaylo Stoyanov and Alejandro Ayuso García.  
This coursework proposes a novel binary classification model trained on the Don't Patronize Me! dataset to identify patronizing and condescending language directed at vulnerable communities.

---

## The repository contains the following files:

- **README.md**

---

### Python scripts from the Don't Patronize Me! repository that allows loading the Don't Patronize Me dataset and evaluating performance of a model trained on it

- **dont_patronize_me.py**  
- **evaluation.py**

---

### Don't Patronize Me! annotated datasets

- **dontpatronizeme_categories.tsv**  
- **dontpatronizeme_pcl.tsv**

---

### Notebooks used to complete the different tasks in this coursework

- **data_analysis.ipynb**: preliminary analysis of the Don't Patronize Me! dataset  
- **train_dev_split.ipynb**: splits the official train set into internal train set and internal dev set  
- **RoBERTa_baseline.ipynb**: replicates the results of the origianl RoBERTa base baseline  
- **BERT_baseline.ipynb**: baseline BERT model  
- **BoW_baseline.ipynb**: baseline BoW model  
- **data_augmentation.ipynb**: analysis of data augmentation as a potential model performance improvement  
- **data sampling-ipynb**: analysis of data sampling as a potential model performance improvement  
- **RoBERTa_multiclass.ipynb**: analysis of using multiclass classification with annotator scores as a potential model performance improvement  
- **roberta_finetuning_stage1.ipynb**: conducts first wave of hyperparameter search  
- **roberta_finetuning_stage1.5.ipynb**: conducts second wave of hyperparameter search  
- **roberta_finetuning_stage2.ipynb**: conducts the last wave of hyperparameter search and produces PCL label predictions on the official Don't Patronize Me! dev and test sets  
- **analysis.ipynb**: analysis of final model performance

---

### Don't Patronize Me! dataset augmented through back translation

- **chinese_augmented_train_set.csv**  
- **french_augmented_train_set.csv**  
- **german_augmented_train_set.csv**  
- **italian_augmented_train_set.csv**  
- **spanish_augmented_train_set.csv**  
- **mixed_augmented_train_set.csv**

---

### Paragraph ids of the official train and dev sets

- **dev_semeval_parids-labels.csv**  
- **train_semeval_parids-labels.csv**

---

### Paragraph ids of the internal train and dev sets

- **internal_train_par_ids.csv**  
- **internal_dev_par_ids.csv**

---

### Don't Patronize Me! official unannotated test set

- **task4_test.tsv**

---

### PCL label predictions of the final model on the official dev and test sets, and evaluation score achieved on the official dev set

- **dev.txt**  
- **scores.txt**  
- **test.txt**
