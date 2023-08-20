# Creating AEM in Docker
* Created Base Image out of Ubuntu Image
* Copy `cq-quickstart-6.5.0` and `license.properties` into aem-base_image folder
* Created Dockerfile Author, Publisher, Dispacher with respective configuration files
* Run `docker-compose up` to create Docker containers running all the AEM instances together
