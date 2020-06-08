# Deepfill
Project of Data Science and Machine Learning.

Keras NN for imputing missing values in categorical columns in a raw dataset.
## Result
Compared with [datawig](https://github.com/awslabs/datawig) on dataset 'mae_train_dataset.csv' in [datawig/examples/](https://github.com/awslabs/datawig/tree/master/examples),
'mae_train_dataset' present 4 columns: color, finish, title, text.

'color' and 'finish' are categorical columns each one with 16 classes, while 'title' and 'text' are free text.

## Test 1
input cols: [title, color] -
output col: [finish]

## Test 2
input cols: [title, text, color] -
output col: [finish]

## Test 3
input cols:  [title, text] -
output col: [finish]

## Charts and other info are available at this [Google Drive directory](https://drive.google.com/drive/folders/1mTDNdoRCiZHTmnVfSXt8oxzFmCM2PeDN?usp=sharing)

 
