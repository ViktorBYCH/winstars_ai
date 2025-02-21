Thank you for the opportunity to complete this interesting test assignment.

Task 1:
The task_1 folder contains the file task1_winstars_ai.ipynb where you can find the code for implementing the first task.
The libraries used are described in the requirements.txt file.
When you run the task1_winstars_ai.ipynb file, you will be prompted to specify the name of the model you would like to choose:
'cnn' - CNN;
'nn' - FeedForwardNN;
'rf' - RandomForestClassifier.
Select the model you need, and the training will begin.
The models_task1 folder contains all 3 models named accordingly.

Task 2:
The task_2 folder contains the dataset_for_ner folder, which I will describe shortly, and the models_task2 folder, where the image classification model based on ResNet is located.
The libraries used are described in the requirements.txt file.
The files images_classifier_task2.ipynb and ner_model_task2.ipynb contain the code for training the image classifier and the NER model for word extraction, respectively.
Unfortunately, repositorie does not contain a trained NER model and image  classifier.
Please do this yourself if your resources allow, or evaluate only the code for its creation otherwise.
During the search for the necessary dataset to train the NER model, I could not find the data I needed. Therefore, I took a different approach. In the dataset_for_ner folder, you can see the file animals_sentences_full.csv, which is the source and does not yet have labels.
After running it through the code in the DF_creater_task2.ipynb file, you will get a dataset with basic labels annotated_animals_with_labels_fix.csv, which will be used to train the NER model in the ner_model_task2.ipynb file.
The final step in creating the ML pipeline is the pipeline_task2.ipynb file, where you can enter your question and the path to the image you want to classify.
