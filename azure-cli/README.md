# Building an Azure Cli image from Ubuntu
1. Write the docker file 
2. Run the command to create the docker image <br />
   docker build -t anbu/ubuntu-azure-cli . <br />
   (This command will build the docker image by reading the dockerfile in the current directory. <br />
3. docker images <br />
REPOSITORY                                TAG                 IMAGE ID            CREATED             SIZE <br />
anbu/ubuntu-azure-cli                     latest              82c129c28fef        47 minutes ago      1.01GB <br />
4. Run the docker image, <br />
   docker run --rm -it anbu/ubuntu-azure-cli bash <br />
   -it -> interactive terminal <br />
   --rm -> remove the container instance, once exited <br />
   
