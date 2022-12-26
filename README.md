# ElderCareApplication

### CSE 696: University of Louisville
 ###### Created by: Emily Fautz
  
  Application is made of:  
  
  <b>Front End: </b> Angular 14  
  
  <b>Back End: </b> .Net API, Entity Framework as Database Mapping, Azure SQL Database  
  
  ### TO BEGIN:
  1) Run the API Solution - ElderCareApi (I recommend using Visual Studio)
        *Open solution file in VS  
        
        *Press Play Button  
        
        --in the browser, Swagger should display a list of the models and CRUD operations able to complete  
        
        **NOTE: pay attention to the port number, you may need it later**
        
        
  ![image](https://user-images.githubusercontent.com/25089720/209490928-c9b7a205-11ad-43e5-aa94-d0b8c0952956.png)
  
  2) Run the Angular Application: AngularElderCareApp  to serve all front end components
         *Open application folder (I recommend Visual Studio Code)
         *Open a new terminal window  
         
        `>ng serve --open`  
        
        *this will take a few moments, if it runs successfully, you will see a new browser window open in port :4200*
        ![image](https://user-images.githubusercontent.com/25089720/209491399-bca21bb4-395a-4162-a495-4e9c88531012.png)
        
 ### Troubleshooting: 
 If the Angular project builds but there is no data, it may not be connected to the right port number (see the port number for the api solution).   
 
 To correct, go to the Angular project. Navigate to the aldercare-api.service.ts file.  
 
 ![image](https://user-images.githubusercontent.com/25089720/209491687-90e593b3-dece-481d-86c2-0fd21588d207.png) 
 
On line 10, change the port number to the one used.  

![image](https://user-images.githubusercontent.com/25089720/209491742-8095d9f0-a0c2-406c-b310-53d2e332caec.png)


Afterwards, if data still doesn't populate, there may be a firewall issue with the Azure Database, please contact me if this happens and I will need to update the firewall settings to include your IP address.


 
 

