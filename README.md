# HelloWorldDocker
This is a sample docker application which prints a text on the console

Use below command for buid a dokcker image from this source code (Here . means Dockerfile contains in the current directory)
docker image  build -t hello-world:1.0 .

Use below command for run above docker image
docker container run hello-world:1.0
