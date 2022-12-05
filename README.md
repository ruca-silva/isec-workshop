## Workshop Challenge

For the purpose of this challenge, you will be given the task of implementing an application to reassemble a much simpler version of IMDB.

It is not mandatory to develop any kind of UI, but if it helps you feel free to do it.

### Tech stack
- Python (you can also use another programming language, but most documentation will be for Python);
- Docker;
- ElasticSearch;
- Flask (webserver);
- Kafka *(bonus challenge)*

### Tools
- Docker;
- VStudio or any other IDE;
- Offset Explorer *(bonus challenge)*

### Application Features
- You should have a web server configured and ready to respond to requests.
- You should have your CRUD (**C**reate **R**ead **U**pdate **D**elete) for movies implemented.
- The API should be using REST architectural style.
- The technology you will be using for storing the information is ElasticSearch.
- Preferably, the information to be stored in ElasticSearch should be done by using ElasticClient. If you have problems using this, feel free to use the normal API.

### Bonus
- Using Kafka, create a Kafka Topic that will be used to storage messages which contain movie information.
- You should have a python application listening to Topic.
- Whenever a message from the topic is read, insert that movie into ElasticSearch


### Resources
https://www.docker.com/blog/how-to-dockerize-your-python-applications/
https://flask.palletsprojects.com/en/2.2.x/quickstart/
https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html
https://elasticsearch-py.readthedocs.io/en/v8.5.2/
https://developer.confluent.io/quickstart/kafka-docker/

