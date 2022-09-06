[![<codecblack>](https://circleci.com/gh/codecblack/Microservices.svg?style=svg)](https://app.circleci.com/pipelines/github/codecblack/Microservices)

## A summary of the project

I was given a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. This project tests ones ability to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

## Instructions on how to run the Python scripts and web app

This is how to run the application:

```bash
  python app.py
```
## A short explanation of the files in the repository.


- .circleci/config.yml: Contains CI/CD configuration for circleci.

- app.py: Entry point of flask application.

- docker_out.txt: Output of docker logs for prediction.

- Dockerfile: Docker image configuration.

- kubernetes_out.txt: Output of docker logs for prediction.

- make_predictions.sh: Bash script that sends data to the flask app for making 			predictions.

- Makefile:  Simplifies complex tasks with procedures and automates building procedure

- run_docker.sh: Automates building the docker image and running the container.

- upload_docker.sh: This is a bash script that automates uploading the image to the dockerhub and automates login as well.

- README.md: This explains the project and its structure.

