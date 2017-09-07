# RESTful Microservice Architecture
## MSC project

---

The weather monitoring system is running on Google Cloud at http://130.211.189.218:8080/

---

### INSTRUCTIONS TO RUN LOCALLY
To run the weather monitoring system locally:
1. Run package.sh which will build and test each service.
2. Launch each service by running run.sh inside each folder.
3. Application is then available at http://localhost:8080
4. Stop all services and run clean.sh to remove.

---

Each service folder contains a Dockerfile to build Docker images. Note that the "weatherCollector" service will have to be modifed with the IP addresses of the Docker machine to run the service from Docker containers.