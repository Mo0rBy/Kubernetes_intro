# Kubernetes
## What is Kubernetes?
When using Docker, we can create containers. These are essentially VM's, but with less restricted deployment properties. Docker is able to more effectively share the resources of the Localhost machine between all of the containers that are in use. Therfore, Docker containers are preferred over standard VM's.

Kubernetes is container orchestration software that manages the the deployment of Docker containers. It is able to restart or replace containers that fail, shut down containers that don't pass the user-defined health checks and it can store and manage sensitive information so you don't have to (e.g. SSH keys, OAuth tokens).



### Advantages
- Better resource allocation and scheduling
- Automated management of container instances
- Allows for Infrastructure as Code
- Increased scalability
- Easier configuration management
- Plenty of documentation and community support

### Disadvantages
- Not very user-friendly
- Steep learning curve
- Logs are hard to read/interpret
