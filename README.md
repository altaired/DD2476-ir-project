# DD2476 Project

## Dataset
The search engine uses [this](https://www.kaggle.com/shivamb/netflix-shows/tasks?taskId=116) dataset from kaggle as its basis. It consists of ~7700 netflix titles.

## Environment
The application requires elasticsearch to be running. For simplicity the movie dataset can be loaded through Kibana. Thus, make sure you have the following setup:

```
elasticsearch (we used version 7.12.1)
kibana (we used version 7.12.1)
```

### Loading the dataset
In order to load the dataset into elasticsearch, do the following: 
1. Open Kibana
2. 

## Dependencies
The application is built using python 3.8 and it requires the following dependecies to run:
```
tkinter (installation instructions below)
tinydb (pip install tinydb)
```

### Installing tkinter
[Instructions here](https://tkdocs.com/tutorial/install.html)

## Database
The project uses tinydb which stores its data in json file. We store the user profiles there and feel free to use our pre-made users or create one yourself. Either way the code assumes the database is located at `./db/users.json`.
