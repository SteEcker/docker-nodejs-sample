# Sample Node.js application

This repository is a sample Node.js application for Docker's documentation.

# Usage

Start the application

```
docker-compose up --build
```

Open a browser and verify that the application is running at http://localhost:3000
Any changes to the application's source files on your local machine will now be immediately reflected in the running container.


Run the following command to run the test script from the package.json file inside a container.

```
docker compose run server npm run test
```
