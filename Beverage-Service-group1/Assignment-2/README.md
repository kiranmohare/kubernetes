To run the docker service we need to give docker-compose up --build command and the project should be build and run.

To run the Beverage Service (Get endpoint), we need to go **http://localhost:8080/beverage/all**
and get all the beverages available.

To run the Management Service (get specific bottle with ID and other services accordingly)  we need to go **http://localhost:8090/management/getBottle?bottleId=1**
