# Spark

This is a repo containing notes pertaining to Spark, mostly concentrating on the python library PySpark which is used to manage Spark clusters. 

## Requirements
Spark has a lot of dependencies that need to be installed, and in practice the Spark cluster is most likely hosted externally anyways. Fortunately Jupyter has created an official docker image which contains all the dependencies for Spark and has a Jupyter environment already setup, making it a great resource for learning. 

The only requirements are that you have docker engine installed. Then simply run the following command in the terminal:

```
docker-compose up
```

After the image has been pulled a container will start up. In the terminal you can see which address the Jupyter Lab environment can be found, should be something like http://127.0.0.1:8888/lab. Any notebooks created in the `work` directory in the Jupyter environment will persist in the `notebooks` directory in this repo. 

