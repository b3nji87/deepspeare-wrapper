# Deep-speare wrapper

Download the original Deep-speare repository and install the needed requirements as stated in [https://github.com/jhlau/deepspeare](https://github.com/jhlau/deepspeare). 

## Train Deep-speare with custom data
We need to copy our custom training data from [link](https://github.com/b3nji87/master-thesis-diversity-in-poetry-generation/tree/main/diversity-in-poetry-generation/training_data) to the root directory of Deep-speare. Therefore, we add *sonnet_train.txt*, *sonnet_validate.txt* and *sonnet_test.txt* to

```
datasets/QuaTrain/<lang>/
```
and copy the corresponding word2vec files *word2vec.bin* and *word2vec.txt* to

```
pretrain_word2vec/QuaTrain/<lang>
```




