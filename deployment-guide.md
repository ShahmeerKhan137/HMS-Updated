Clone the respostiry to local:<br>
> git clone https://github.com/Ashir-Qayyum/hms-microservices-app-docker-compose.git<br>

To Deploy the application locally on docker containers, run the commands:<br>

> cd hms-microservices-app-docker-compose<br>

> docker compose -f docker-compose-for-local-test.yaml up<br>

(to run the application in a detached mode, add the flag -d in the command)<br>

If want to build the application locally in a machine & Deploy, please run:<br>

> docker compose -f docker-compose-for-local-test.yaml up --build<br>

After deployments, access the Application Frontend locally at the URL:<br>

> http://localhost:5173