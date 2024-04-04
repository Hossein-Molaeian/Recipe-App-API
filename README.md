# Recipe REST API

This project revolves around the creation of an advanced REST API utilizing Python, Django REST Framework, and Docker, all developed through Test Driven Development (TDD). It aims to provide a comprehensive solution for handling various functionalities crucial for modern web applications and software.

### Key Features:

- **User Management**: Implementing user authentication, user profile creation, and password management.
- **Object Management**: Functionalities of creating, updating, filtering, and sorting of objects, focusing on recipe, ingredients and tags.
- **Media Handling**: Facilitating the uploading and viewing of images within the API.
- **Best Practice Principles**: Following PEP-8 guidelines, unit testing, and applying Test Driven Development.
- **Scalability and Reusability**: Building a backend that can serve as a foundation for future projects or Minimum Viable Products (MVPs).

## Technologies Used

- **Python**: The core language for backend development.
- **Django REST Framework**: Providing powerful tools for building APIs in Python.
- **Docker**: Facilitating easy setup and deployment of development environments.
- **PostgreSQL**: Configured as the database.
- **GitHub Actions**: Automating code checks.

## How to Setup This Repository

You can follow these steps to run this project locally:

**1. Clone this repository:**
```bash
git clone https://github.com/Hossein-Molaeian/Recipe-App-API.git
```
**2. Install Docker:** <br>

If you haven't already installed Docker on your machine, visit the [official Docker website](https://www.docker.com/products/docker-desktop/) and follow the instructions to download and install Docker for your operating system.

**3: Setup Local Development Environment:** <br>

Navigate to the project directory and use Docker Compose to build the Docker containers and set up the local development environment:
```bash
docker-compose up --build
```
**4: Run Tests:** <br>

Execute unit tests to ensure code correctness and functionality:
```bash
docker-compose exec app python manage.py test
```
**5: Interact with the API:** <br>

With the Docker containers running, you can interact with the API using tools like curl, Postman, or directly through a web browser. The API endpoints should be accessible at http://localhost:8000/api/docs.

**6: Shut Down the Containers:** <br>

Once you're finished working with the project, you can stop and remove the Docker containers:
```bash
docker-compose down
```
## Screenshots

![1](https://github.com/Hossein-Molaeian/Recipe-App-API/assets/96408257/273deb4e-ea37-464d-a98d-3107bd4aa26f)


![2](https://github.com/Hossein-Molaeian/Recipe-App-API/assets/96408257/c34ffb41-4c8c-4df2-a20f-ebcb7a053813)


![3](https://github.com/Hossein-Molaeian/Recipe-App-API/assets/96408257/68beaabb-118f-4f09-bf41-6be5d4193e1a)


##

**Thank you for exploring this repository!**
