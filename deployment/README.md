## ML-Model-Flask-Deployment
This is a demo project to elaborate how Machine Learn Models are deployed on production using Flask API

### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

### FORMAT

MAKE SURE THAT THE FILES IN YOUR DEPLOYMENT FOLDER ARE IN THE SAME MANNER AS IN MY DEPLOMENT FOLDER                
[ Because if files in that order and format FLASK can understand where to Look for them .]

HTMLS FOLDER SHOULD BE KEPT IN THE DEFAULT DIRECTORY OF YOUR SERVER APPLICATION FORM WHICH IS WILL ACCESS IT.

Note -                                                                                                                     
       INSTALL FLASK FIRST USING pip command                                                                            
       TO CREATE A NEW PROJECT FOLLOW  - https://www.jetbrains.com/help/pycharm/creating-flask-project.html            
       INSTALL ALL THE REQUIRED MODULES FOR APPLYING ML ALGORITHMS FIRST

### Running the project
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -
```
python model.py
```
This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://localhost:5000

You should be able to view the homepage as below :
![alt text](http://www.thepythonblog.com/wp-content/uploads/2019/02/Homepage.png)

Enter valid numerical values in all 3 input boxes and hit Predict.

If everything goes well, you should  be able to see the predcited salary vaule on the HTML page!
![alt text](http://www.thepythonblog.com/wp-content/uploads/2019/02/Result.png)

4. You can also send direct POST requests to FLask API using Python's inbuilt request module
Run the beow command to send the request with some pre-popuated values -
```
python request.py
```
