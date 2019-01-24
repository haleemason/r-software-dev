# r-software-dev
Repo for the course sequence Mastering Software Development in R, available on Coursera. Covers R software development for building data science tools.

## Docker
Docker performs operating-system-level virtualization, also known as "containerization" and provides a way for applications to run in a container with all packages and dependencies pre-installed. A Docker container has been built to contain all needed libraries for this course.

### Docker Set up

1. Download and install Docker from the following URL: https://www.docker.com/
2. Open a terminal, and navigate to the "docker" folder of the repo: `cd src/main/docker`
3. Type the following command into terminal: `docker-compose up -d`
4. In your internet browser navigate to: localhost:8787
5. You should now see an RStudio instance.
    * username: rstudio
    * password: rstudio
6. The rstudio instance can be stopped by typing the following command in your terminal: `docker-compose down`