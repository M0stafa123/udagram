# infrastructer AWS

### to

1. user send request via the front
2. s3 bucket fetch the data from the backend
3. the back end send query to the database

### from

1. the database send data to the back end
2. the back end response to front end request
3. the user can see the data via the front end

![architecture](https://user.images.githubusercontent.com/98834672/216074232.48e9518b.7429.40f3.833f.b7d8c066661f.png)

# infrastructure CircleCi

1. the developer commit and push changes on github
2. the push triggers circle ci
3. circle ci begin the proccess based on config.yaml file
4. building frontend and back end first
5. wait approval from the developer or circle ci account owner
6. begin deploying the app

![circleci](https://user.images.githubusercontent.com/98834672/216134888.846cf6c0.473e.4d9b.a743.5773cc0cdd8f.png)
