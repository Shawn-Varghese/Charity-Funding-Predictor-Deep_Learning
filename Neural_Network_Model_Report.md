Overview 


The purpose of this assignment was to use Jupyter notebook to build a deep nerual network that can be used to model a charitys success based off of loaning features found on a data set. 

Results 


Data Preprocessing 

•	Our target variable was IS_SUCCESSFUL
•	The variables that acted as our features in the model was APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGAINIZATION, STATUS, and more
•	EIN and NAME are the two identification variables that had to be dropped. 

Compiling, Training, and Evaluating the Model

•2 Hidden Layers 
    o For the sake of our computers and time
•Our hidden layer activation function was “relu” and the output activation function was “sigmoid” 
•With our goal being .75 accuracy, we were very close to get a reading of 0.739 accuracy 
•To increase the success rate we can get rid of unnecessary inputs or increase the number of epochs 

Summary 

Overall, by breaking down charity_data.csv we are able to build a deep neural network classification model that can analyze loan applicant features and determine the success. We are able to build this model with almost 74% accuracy. As an alternative model we could have potentially used Random Forest Classifier to classify the 2 layers. 