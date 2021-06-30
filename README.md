# DOCKER INTEGRATION WITH AWS ECS

-  "I Didn't Know I Could Do That with Docker - AWS ECS Integration"
- https://www.youtube.com/watch?v=AVLwI_yZDVs&t=63s


# SETUP

- setup Docker: https://docs.docker.com/get-docker/
- setup Docker compose cli (we need it to execute "docker context create ecs myecscontext"): wget https://github.com/docker/compose-cli/releases/download/v2.0.0-beta.4/docker-compose-linux-amd64
- Docker ECS integration: https://docs.docker.com/cloud/ecs-integration/

# SOME COMMANDS

- show docker context: docker context ls
- create a new docker ecs context: docker context create ecs myecscontext
- create AWS resources: docker compose up
- see AWS CloudWatch logs: docker compose logs
- see AWS CloudFormation structure: docker compose convert