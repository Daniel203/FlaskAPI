# FlaskAPI
A simple API made with python FLASK

### API Endpoints

| Method         | URL     | Definition |
|--------------|-----------|------------|
| GET | ```/todo/api/v1.0/tasks/<int:task_id> ```     |      Get task by id   |
| GET      | ```/todo/api/v1.0/tasks```  | Get all tasks       |
| POST      | ```/todo/api/v1.0/tasks```  | Create a new task       |
| PUT | ```/todo/api/v1.0/tasks/<int:task_id>```      |     Update a task using id    |
| DELETE | ```/todo/api/v1.0/tasks/<int:task_id>```      |     Delete task by id    |
