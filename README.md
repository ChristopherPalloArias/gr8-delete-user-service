# Delete User Service

This is the microservice for delete User in the +Kotas App.

## Group Members

- Christopher Pallo
- Brayan Dávila

## Table of Contents

1. [Microservice Description](#microservice-description)
2. [Installation](#installation)
   - [Requirements](#requirements)
   - [Clone the Repository](#clone-the-repository)
   - [Install Dependencies](#install-dependencies)
   - [Start the Server](#start-the-server)
   - [Evidence](#evidence)
3. [Usage](#usage)
   - [Verify Server Functionality](#verify-server-functionality)
   - [List the Users](#list-the-users)


## Microservice Description

The `delete-user-service` microservice is responsible for managing the list of users in the +kotas App. Allows you to list products using an HTTP DELETE request to the corresponding route.

## Installation

### Requirements

- Node.js
- npm (Node Package Manager)

### Clone the Repository

```sh
https://github.com/ChristopherPalloArias/gr8-delete-user-service.git
cd list-user-service
```

### Install Dependencies
```sh
npm install
```

### Starting the Server
Before starting the application you must change the database credentials in the index.js file if you want to use the application locally and independently, this is because initially the application is configured to be used in conjunction with the rest of Microservices.
Repository: [https://github.com/ChristopherPalloArias/kotas-frontend](https://github.com/ChristopherPalloArias/kotas-frontend.git)

### Evidence
![image](https://github.com/user-attachments/assets/4d6303f5-622e-45fa-a7d8-5c26854a367a)

## Usage
### Verify Server Functionality

Method: DELETE  
URL: `[http://localhost:8085/](http://gr8-load-balancer-users-1719093065.us-east-2.elb.amazonaws.com:8085/)`  
Description: This route displays a message to verify that the server is running.
![image](https://github.com/user-attachments/assets/d3fcc87e-b503-4728-8df9-481bfab798a9)
