# Docker Compose for Aparavi

These are the steps to set up Aparavi using Docker Compose:

1. **Download the latest docker-compose.yaml**: Download docker-compose.yaml, which contains the necessary Docker Compose configuration files for Aparavi, to a directory of your choice. This directory with be populated with Aparavi data so it should be sized accordingly.

2. **Navigate to the directory**: Open a terminal or command prompt and change the directory to where you created a folder that includes the docker-compose.yaml.

3. **Run "docker compose up -d"**: Start the Aparavi services defined in the Docker Compose configuration file in detached mode (-d), which means they will run in the background. Make sure you have Docker installed and running on your system before executing this command.

4. **Navigate to http://localhost**: After the services are up and running, access Aparavi by opening a web browser and navigating to http://localhost:xxxxx. Where xxxx is the port assign to the platform container.

5. **Login to Aparavi using root:root**: Once you access Aparavi via the provided URL, log in with the username "root" and the password "root" as instructed.

Remember to replace "localhost" with the appropriate hostname or IP address if you're accessing the service from a remote machine. Also, ensure that the necessary ports are open and not blocked by any firewall settings.
