# Microservices and gRPC

1. Create email sender micro-service that will take a `email` and `full_name` (both of those fields are required) of the user and send him a welcoming message. Your service should return `bool` value to specify whether message was sent or not. (you will need to define `.proto` file fot this and your service can just do simple `println` in the `cli`)

2. Update (http server)[https://github.com/snfgo/go-training/tree/master/tasks/http] you've developed in the previous challenges to store email in the user storage. 

3. Add call to your gRPC service when creating the user inside yor http server to send him a welcome email. (`POST` /users/create - create user endpoint)

4. `*` Add unit tests to your service.

