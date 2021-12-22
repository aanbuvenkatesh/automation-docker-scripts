# Running Dynamo DB locally in Docker
1. Download the dynamo-db.yml file inside a new folder
2. Create a folder called "dbdata" to store all the data records in the host system.
3. Run the command to start the dynamo db locally<br />
   docker compose -f dynamo-db.yml up --build -d <br />
4. Once the container is successfully up and running, access the dynamodb shell at localhost:8001/shell
5. Optionally a dev-network is created. Other containers can be associated to this network.
