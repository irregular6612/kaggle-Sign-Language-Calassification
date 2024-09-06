2024 Outta-3rd Competition P1 Notebook
Sign Language Classification


Url : https://www.kaggle.com/competitions/2024-outta-basic-p-1/overview
Dataset : https://www.kaggle.com/datasets/datamunge/sign-language-mnist

Task-type: classification
Model: pretrained VGG16

Short Summary:
- Classify the sign image to alphabet labels
- Fine tuning pretrained VGG16 with based on CNN model.
(use feature extractor of VGG16 and add classifier)

Result:
- train_acc: 1.0
- test_acc: 1.0
- rank: 1/62

Key Point:
- reduce freeze layer -> at the end, I don't freeze any layer. 

Last edited: 24/09/06
