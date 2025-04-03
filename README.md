# Docker Overview
Docker provides an ```independent environment``` where applications run, known as a ```container```.

To create an ```Ubuntu container```, use the following command:
```
docker run -it ubuntu
```

## Docker Components
### 1. Docker Containers
A ```Docker container``` is a single unit that ```bundles an application along with its dependencies```, ensuring consistency across different environments.
#### Key Properties of Containers:
- Portable – Can run on any system with Docker installed.

- Lightweight – Uses fewer resources compared to virtual machines.

- Isolated – Provides a separate environment for different applications on the same machine.

### 2. Docker Images
A ```Docker image``` is an ```executable file``` that contains all the instructions required to build a container.

####  Analogy:
- A ```Docker image``` is like a ```class``` in programming.
- A ```Docker container``` is like an ```object``` (instance) of that class.


#### Key Difference:
- A ```Docker image``` is ```static``` (a blueprint).
- A ```Docker container``` is ```dynamic``` (a running instance of an image).


To check if Docker is installed on your system, run the following command:
```
docker -v
```
<img width="1280" alt="Screenshot 2025-04-04 at 12 01 46 AM" src="https://github.com/user-attachments/assets/ca268b81-7de7-48ad-b790-0daf2f83c253" />



