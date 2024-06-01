# Task Manager

Task Manager is a simple Ruby on Rails application that allows users to create, read, update, and delete tasks. This project was created as a learning exercise to understand the basic workflow and concepts of Rails, including routing, MVC architecture, and database management.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Database Setup](#database-setup)
- [Usage](#usage)
- [Running Tests](#running-tests)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create, read, update, and delete tasks.
- Tasks have a title and description.
- Basic validation to ensure that tasks have both a title and description.
- Navigation links to easily move between different parts of the application.

## Getting Started

### Prerequisites

To run this project, you will need to have the following installed on your system:

- Ruby (version 2.7.0 or later)
- Rails (version 6.0 or later)
- Postgresql (for database)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/task-manager.git
   cd task-manager
   ```

2. Install the required gems:

   ```sh
   bundle install
   ```

### Database Setup

1. Create the database:

   ```sh
   rails db:create
   ```

2. Run the migrations:

   ```sh
   rails db:migrate
   ```

## Usage

1. Start the Rails server:

   ```sh 
   rails server
    ```

2. Open your web browser and go to `http://localhost:3000` to see the application in action.


