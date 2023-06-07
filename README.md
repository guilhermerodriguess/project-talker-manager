# Talker Manager

The Talker Manager project is an API for managing speakers (talkers). It allows for the registration and search of speakers, as well as various operations related to speaker management.

## Project Objective

The main objectives of the Talker Manager project are:

- Apply knowledge in Express, Node.js, and MySQL.
- Develop a CRUD application using Node.js and Express.

## Features

The Talker Manager project offers the following features:

- User registration: Allows users to create a login to access the application.
- Speaker registration: Enables the registration of speakers by providing their information.
- Update speaker information: Allows the editing of existing speaker information.
- Get all speakers: Retrieves the information of all registered speakers.
- Get speaker by ID: Retrieves the information of a specific speaker by their ID.
- Filter speakers by name: Filters the speakers' information based on their name.
- Delete speaker: Deletes the information of a specific speaker.

## Prerequisites

Before running the application, make sure you have the following tools installed on your machine:

- Clone the repository:

  ```
  git clone git@github.com:your-username/project-talker-manager.git
  ```

### Running the Application without Containers

To run the application without containers, follow these steps:

1. Navigate to the backend folder:

   ```
   cd project-talker-manager/app/backend
   ```

2. Install the dependencies:

   ```
   npm install
   ```

3. Start the application:

   ```
   npm start
   ```

### Running the Application with Containers

To run the application with containers, follow these steps:

1. Navigate to the backend folder:

   ```
   cd project-talker-manager/app/backend
   ```

2. Update the `docker-compose.yml` file:

   ```
   Update the necessary configurations in the docker-compose.yml file.
   ```

3. Enter the container's terminal:

   ```
   docker exec -it talker_manager bash
   ```

## Extras Features

In addition to the requested features, the project includes extra features and ongoing refactoring. The additional features will be listed and updated as new developments are made.

Thank you for exploring the Talker Manager project! If you have any questions or need further information, please feel free to reach out.
