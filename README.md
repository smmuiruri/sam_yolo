# About
The application is an e-commerce website that doubles-up as a dashboard where you can load retail products on to the site. You can test out this functionality by adding a product through the provided form 

## Navigate to the repository at below link and clone it
 https://github.com/smmuiruri/sam_yolo

### Application comes with all prerequisites and therefore no need to install or run them
- node
- npm installed
- npm started
- mongo

#### The application is packaged into three containers which will automatically build and start upon running the start commands
- client container (launched by Dockerfile inside Client folder)
- backend container (launched by Dockerfile inside Client folder)
- mongodb container (launched from docker-compose file in the main app directory)

#### Networking
-We have Client, API, and the Database, all running in separated containers with only one command. The three containers are interconnected in a bridge network
-Client runs on ports 3000
-Api/backend runs on port 5000

###### Run the folllowing to start the app
- docker-compose up --build (docker-compose file in the main directory of the app contains build and run orchestration)

####### Open the application using the localhost ip after spinning the app at 
http://0.0.0.0:8080

 - Go ahead and add a product (note that the price field only takes a numeric input)

