
# EDVORA Assignment

This assignment was about integrating a feed application with FastAPI and WebSockets. By opening the server link in different tabs the users can interact with each other and read each other's messages.The users in each tabs are provided with random user numbers which is unique for that particular session to distinguish them from each other.


## Tech Stack

FastAPI and WebSockets




## Installation

Install FastAPI using pip , with [all] we can install all the necessary dependencies or we can use 'requirements.txt' file to install the dependencies.

```bash
  pip install fastapi[all]
```
After completing the code , the server can be started with -

```bash
uvicorn main:app --reload
```

Here 'main' is the name of the file in which the code has been written and 'app' is the instance of the class FastAPI.

### venv -
Before starting it is a good practice to start the project in a separate isolated environment using 'venv' -

```bash
py -m venv venv
```


## Screenshots

![Homepage](https://github.com/anuragshukla07/EdvoraInternshipTask/blob/master/Screenshots/WebSocket%20CHAT%20-%202.jpg)
![Homepage](https://github.com/anuragshukla07/EdvoraInternshipTask/blob/master/Screenshots/WebSocket%20CHAT%20-1.jpg)
