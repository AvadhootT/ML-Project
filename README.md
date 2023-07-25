#End to end machine learning project.

Modules we created in componenets-->
1. data_ingestion
2. data_transformation
3. model_trainer
are mainly for training purpose only.

Pipeline—>
1. training pipleine
2. prediction pipeline
all the modules we made in the components we will be using in the pipeline

utils.py-->
we will write all the functionalities that can be used over all the application

login.py-->
for login page

exception.py-->
handling all the exception cases
give all the details line no which python script the error is, it going to be same for all the code

logger.py-->
track every execution

Whenever we will get the exception-->
1. take that exception
2. logging into the logger file
3. and use log.info to put it inside the file