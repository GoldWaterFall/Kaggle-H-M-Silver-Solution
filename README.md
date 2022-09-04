# Kaggle-H-M-Silver-Solution

Kaggle H&amp;M Multimodal recommends 5% silver solution

Address of the competition:https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations

Run steps:

1 Download the dataset

2 Run code/data_prepare, the main purpose of this step is to generate parquet files, which runs fast

3 Run code/recall_sort, which contains two parts: recall and sort

Some dependent packages need to be installed by yourself

pandas
numpy
lightgbm
pyarrow
pickle
tdqm

Running requires a large amount of memory, 64G memory is recommended
