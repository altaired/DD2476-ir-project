# DD2476 Project


## Environment
The application requires elasticsearch to be running. For simplicity the movie dataset can be loaded through Kibana. Thus, make sure you have the following setup:

```
elasticsearch (we used version 7.12.1)
kibana (we used version 7.12.1)
```

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
