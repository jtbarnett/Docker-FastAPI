# Python and Docker web app project with FastAPI (similar to Flask)

Built with Python version 3.9.1 and Docker version 20.10.0.

## Purpose

The purpose was to create a simple web application with Python and FastAPI. The project can be deployed with Docker.

## Build and Run

To build the project, type `docker build -t python-fastapi .` into your terminal. To run the project, type `docker run -p 8000:8000 python-fastapi` in your terminal. Make sure to specify the internal and external port for Docker.