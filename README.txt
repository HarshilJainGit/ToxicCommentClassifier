The zip contains only the notebook files containing the code and a readme file. All the other supporting files are on 

Github (https://github.com/gaurav199494/multilabel-comment-classification)



Steps to run:

1) Unzip the folder

2) Make a new folder called ‘data’ which contains the dataset (data folder on Github)

3) You will also have to download the word embedding file from the following URL:  (https://fasttext.cc/docs/en/english-vectors.html)

4) In the unzipped folder containing the Jupiter notebook files, create a new folder called ‘crawl-300d-2M.vec’. Place the downloaded word embedding file in this folder. 

5) The main folder will contain 5 Jupyter Notebook files and 1 README file

6) Open command prompt and navigate to the unzipped folder containing all the content mentioned above.

7) A new tab would open on the browser for Jupyter Notebook.





Logistic Regression: (logistic.ipynb)

Once you run all the code blocks, finally a results csv file called ‘logistic_results’ would be generated. This file will contain the actual predictions for all 6 classes of a comment.

After this you can run the create_cm file by giving in the correct name to the paths and files. This would generate accuracy and loss values for all 6 classes. And finally it

 would generate a file called ‘average_logistic’ containing the accuracy, balanced accuracy, log loss and hamming loss.



Naive Bayes SVM: (NBSVM.ipynb)

Once you run all the code blocks, finally a results csv file called ‘NBSVM_results’ would be generated. This file will contain the actual predictions for all 6 classes of a comment.

After this you can run the create_cm file by giving in the correct name to the paths and files. This would generate accuracy and loss values for all 6 classes. And finally it

 would generate a file called ‘average_NBSVM’ containing the accuracy, balanced accuracy, log loss and hamming loss.



CNN: (ConvolutionalNeuralNetwork.ipynb)

Once you run all the code blocks, finally a results csv file called ‘cnn_results’ would be generated. This file will contain the actual predictions for all 6 classes of a comment.

After this you can run the create_cm file by giving in the correct name to the paths and files. This would generate accuracy and loss values for all 6 classes. And finally it

 would generate a file called ‘average_cnn’ containing the accuracy, balanced accuracy, log loss and hamming loss.



It also has a file for Data Visualization (DataVisualization.ipynb)which contains plots related to the data.
