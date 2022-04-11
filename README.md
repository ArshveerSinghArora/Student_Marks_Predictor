
# Student Marks Predictor 

This is a mini project in which I have deployed a Machine Learn Model on production using Flask API.

## Aim -:

In this project I have been given data with Study Hours & Student Marks.
Using the data in csv file("student_info.csv"), we will check that on studying how much hours you will get how much marks.

## Perquisites -:

To run this, you must have Scikit Learn, Pandas (For Machine Learning Model) & Flask (for API) installed.

## Project Structure -:

This Project contains three major parts -:
1. Student_marks_predictment.ipynb - This contains code for Machine Learning Model to predict marks based on training data in "student_info.csv" file.
2. app.py - This contains Flask APIs that receives employee details through GUI, computes the predicted value based on our model & return it. 
3. templates - This folder contains the HTML template to allow user to enter Study Hours & displays the predicted student marks.

## Running The Project -:

1. Open file "Student_marks_predictment.ipynb" (Jupyter File Notebook) & then run it. (this is step for creating model),(After running it, you will obtain model "student_mark_predictor.pkl", which you will later on use on flask)
2. Then, open the "templates" folder in which there will be website for the model.
3. To run that website, run "app.py" on Spyder that will give you address like this –

####

![Picture1.png](https://github.com/ArshveerSinghArora/Student_Marks_Predictor/blob/master/static/images/Picture1.png?raw=true)

4. copy address & run it on browser.
5. it will open webpage like this –

####

![Picture2.png](https://github.com/ArshveerSinghArora/Student_Marks_Predictor/blob/master/static/images/Picture2.png?raw=true)

6. on running it will give output like this –
####

![Picture3.png](https://github.com/ArshveerSinghArora/Student_Marks_Predictor/blob/master/static/images/Picture3.png?raw=true)
