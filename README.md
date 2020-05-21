To Run Airflow Dag using YMAL Config file in Locally:

  step 1 : Clone this repository to your local machine 
  
  step 2 : Run Airflow Service using following command (it will start airflow web UI at port 8080(you can also check the port number in airflow.cfg)
  
       > airflow webserver :
  
  step 3 : to check the list of your dag in command line use:  
  
       > airflow list_dags
  step 4 : Run scheduler to see the dag in Web-UI       
       
       > airflow scheduler
   
         

