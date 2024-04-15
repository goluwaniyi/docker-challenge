## Summary of my work
This project contained two challenges: 3 and 4. In **Challenge 3**, we were tasked to add a database service to the existing application layer and make them work together, which I accomplished. In **Challenge 4**, we were tasked with researching how to scale a Node.js instance from one to three, which was also accomplished.

### Challenge 3
In this challenge, I was able to successfully build and connect a MariaDB database service to the existing layer. I modified the `Dockerfile` as needed and added the necessary service definitions to the `docker-compose.yml` file. I went ahead to make other services like the Node.js service dependent on the database service to start, as is recommended and commonly done. I also successfully used a `.env` file to set the environment variables for the Docker network which the Node.js and database services were able to access and use.

### Challenge 4
In this challenge, I researched how to scale my Node.js service to three instances. Using the knowledge gained from the research, I was able to successfully scale the instance and document the steps taken and results achieved. Furthermore, I researched the benefits of such a process and outlined them in my journal.

### What I learned
- I learned how to add a database service to an existing application layer
- I learned how to write an environment variable file and use this in my application layer
- I learned how to successfully edit and modify a `Dockerfile` and `docker-compose.yml` file
- I learned how to edit and modify a configuration file for nginx
- I learned how to specify multiple servers in an upstream block to handle several instances of my Node.js app
- I understood the benefits of having multiple instances of a service as opposed to one
