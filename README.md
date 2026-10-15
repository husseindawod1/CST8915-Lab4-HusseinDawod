# CST8915-Lab4-HusseinDawod

## Demo Video Link
[CST8915 Lab 4 Demo Link](https://www.youtube.com/watch?v=v_8HuE8HyUY)

## Reflection Questions

### What are the main differences between a Docker image and a Docker container?
A Docker Image is a read-only blueprint of a container and a container is an instance of that blueprint


### Explain how Docker's layered architecture improves efficiency.
The immutable layers prevent inconsistency and the mutable layer at runtime allows for efficient processing.

### Why does each container get its own writable layer?
So that in the moment of runtime, any temporary changes can be made respective to that specific runtime.

### What are the benefits of using Docker Compose over running containers individually?
Docker Compose organizes containers of the same host in one place.