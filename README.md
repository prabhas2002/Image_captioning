# Image_captioning
Repository for image captioning using CNN and LSTM

## Dataset
Used Flikr8k dataset wich consistes of 5 captions for each image in it.(and containes aroung 8k images like that)

## Eval metric
Used BLEU between the predicted caption and original captions and can take average of them.


## Method

1) Used pretrained Resnet for CNN encoder.(with grad=False) except for the last layer which I added.
2) Then, this embedding will be used as hidden vector for LSTM and seq2seq training will happen.(where the truth is the right shifted ones of the original caption.)


## Results
For results , once can see at the bottom of the ipynb notebook.




