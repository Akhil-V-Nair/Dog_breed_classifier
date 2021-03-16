# Dog_breed_classifier
Deep learning with Unstructured data using transfer learning with resnet50 Architecture


Part 1:

Build a dog breed image classification model with the architecture specified below.
Dataset - https://www.kaggle.com/c/dog-breed-identification/data
● The classifier should only predict scores for these breeds : beagle, chihuahua, doberman,
french_bulldog, golden_retriever, malamute, pug, saint_bernard, scottish_deerhound,
tibetan_mastiff.
● Any of these frameworks can be used : Tensorflow, Keras, Pytorch, Caffee.
● The classifier should only be built using Resnet50 CNN architecture.
● Evaluation metrics i.e Accuracy, Confusion Matrix, F1 Score, ROC-AUC Score shall be calculated
on test data.



Part - 2: ( Extra brownie points! )

Build an API around the model inference pipeline which takes in an Input image in Base64 and
responds with the appropriate dog breed. Any framework of choice can be used but the API needs
to follow REST architecture and shall be deployed publicly.
● The input format needs to be :
{
image : <base64 encoded image>
}
● Expected response:
{
breed : <resulting label>
score : <prediction score of the above label >
}
● A working api endpoint needs to be submitted as a result of this assignment.
