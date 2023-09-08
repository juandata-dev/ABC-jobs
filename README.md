# ABC Jobs Motor de emparejamiento Microservice

Experiemento para la materia Arquitecturas Agiles de la Maestria en Ingenieria de software de Uniandes MISO.



## Tasks

### Setup Docker Environment
You'll need to install docker https://docs.docker.com/install/. Open a new terminal within the project directory and run:

1. Build the images: `docker-compose -f docker-compose-build.yaml build --parallel`
2. Run the container: `docker-compose up`

### Import the Postman Collection
You'll need to install postman https://www.postman.com/downloads/
1. Import the file ABCJobs.postman_collection.json
2. You need to login to your Postman account to be able to run performance test
3. Within the ABC Jobs collection select the performance testing folder
4. Click on run and select the performance tab
5. Configure the time and the number of virtual users and finally execute the test clicking on run button
