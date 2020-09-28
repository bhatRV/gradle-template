Project Name : Food Truck Near Me 

Author : RASHMI VISHNU
#NOTE: #

######### SWAGGER URL:####
1.start the application using bootRun
2.browser : http://localhost:8080/swagger-ui.html#/find-food-nearMe

######### ASSUMPTIONS and SCOPE for ENHANCEMENT :####
1. Extensive test cases to cover more scenarios can be added
2. Validations can be enhanced to include more on the inputs. Basic validations are provided for now. 
3. User Interface can be provided
4. Default port will be tomcat's default port -8080
5.uses internal cache for storing the data. Can be enhanced to use H2 

#######################HOW TO RUN THE SIMULATION###########################

#To run from Eclipse/IntelliJ

Run as application "FoodNearByApplication.java"

#To build the application

./gradlew clean build

###To run the application from command prompt or using gradle:####

./gradlew bootRun

#### Scenarios covered#####

3. To Retrieve the nearby food truck information use POST on this url:  http://localhost:8080/api/v1/findtrucks
   
#### PRE configured Data#####
 
