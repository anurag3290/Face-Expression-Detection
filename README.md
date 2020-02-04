# Face-Expression-Detection (Basic)
Data link: https://drive.google.com/drive/folders/16UjLYyp9olGSmnGBpAaDeZ2W981CZD_k?usp=sharing

The database contains 213 images of 7 facial expressions (6 basic facial expressions + 1
neutral) posed by 10 Asian female models. Each image has been rated on 6 emotion
adjectives by 60 Japanese subjects. Images are in .tiff format, no compression.
Facial Expression of the images are encoded in the name of the image file as:
[PersonName].[ExpressionName][Number of the respective expression][ImageID].tiff

Example:
KA.NE1.26.tiff ->
PersonName: KA
ExpressionName: NE
Number of the respective expression: 1
ImageID: 26

Expression Codes:
HA: Happy
SA: Sad
SU: Surprise
AN: Angry
DI: Disgust
FE: Fear
NE: Neutral

Problem Statement:
To train a model which can identify the expression of the person in a given
image as input.
Evaluation Metric: F1-Score along with Classification Report (Using sklearn.metrics.classification_report).
