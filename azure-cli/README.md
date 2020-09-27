# Building an Azure Cli image from Ubuntu
1. Write the docker file 
2. Run the command to create the docker image 
   docker build -t anbu/ubuntu-azure-cli .
   (This command will build the docker image by reading the dockerfile in the current directory.
3. docker images
REPOSITORY                                TAG                 IMAGE ID            CREATED             SIZE
anbu/ubuntu-azure-cli                     latest              82c129c28fef        47 minutes ago      1.01GB
4. Run the docker image, 
   docker run --rm -it anbu/ubuntu-azure-cli bash
   -it -> interactive terminal
   --rm -> remove the container instance, once exited
   