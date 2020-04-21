# User Task Manager
---

This repository comprises of two git submodules
- user-task-service (spring boot data rest with h2)
- user-task-ui (angular)

To clone the repository with the submodules:
```
    git clone -recurse-submodule https://github.com/adnanmamajiwala/user-task-manager.git
``` 

To start the application, make sure you have docker installed, then navigate to the cloned repository location and run:
```
    docker-compose up
```

Once the docker compose is up :
- User-task-ui can be accessed on `http://localhost:9000`
- User-task-service actuator can be aKccessed on  `http://localhost:9080/actuator`
- Api documentation (swagger-ui) `http://localhost:9080/swagger-ui.html`

