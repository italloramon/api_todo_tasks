# How to use

Requirements: 
- Install django and django rest framework

    ```pip install django```<br>
    ```pip install djangorestframework```
 
- Now download the code as ZIP, in the directory open the bash and type:

    ```python3 manage.py runserver```
  
-  If  you access http://127.0.0.1:8000/api/ you should see this
<a href="https://ibb.co/3RyHPVk"><img src="https://i.ibb.co/XYZTG6V/apioverview.png" alt="apioverview" border="0" /></a>

### List Tasks
- Access http://127.0.0.1:8000/api/task-list/ you should see all the tasks. Empty, if none tasks have been created.
<a href="https://ibb.co/XpXHMkV"><img src="https://i.ibb.co/3W1KQYk/api2.png" alt="api2" border="0"></a>

### Detail View
- Access http://127.0.0.1:8000/api/task-detail/[task-id]/ you should see the details about this task.
<a href="https://ibb.co/g91Bhp8"><img src="https://i.ibb.co/wgHxjXq/api3.png" alt="api3" border="0"></a>

### Create
- Access http://127.0.0.1:8000/api/task-create/ then submit your task.
<a href="https://ibb.co/t8HZ0B9"><img src="https://i.ibb.co/bz6H41k/api4.png" alt="api4" border="0"></a>

###  Update
- Access http://127.0.0.1:8000/api/task-update/[task-id]/ then submit your modified task.
<a href="https://ibb.co/C5YkF2z"><img src="https://i.ibb.co/SXMhprP/api5.png" alt="api5" border="0"></a>

### Delete
- Access http://127.0.0.1:8000/api/task-delete/[task-id]/ then click in the delete button.
<a href="https://ibb.co/RH1SYFd"><img src="https://i.ibb.co/123n7gj/api6.png" alt="api6" border="0"></a>

### Final View
- Finally,  we should see this in the task list<br>
<a href="https://ibb.co/6Z0ZNk9"><img src="https://i.ibb.co/YWBWbxn/apifinal.png" alt="apifinal" border="0"></a>
