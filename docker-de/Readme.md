# Docker 
What is Docker used for?
It enables the quick and consistent deployment of your applications. It simplifies the development lifecycle by enabling developers to collaborate in standardized environments using local containers, ensuring uniformity for applications and services. Containers prove effective for continuous integration and continuous delivery (CI/CD) workflows.

Consider the following example scenario:

- Developers write code on their local machines, sharing progress with colleagues through Docker containers.
- Docker is utilized to deploy applications to a test environment, facilitating both automated and manual testing.
- In the presence of bugs, developers rectify them in the development environment and redeploy to the test environment for validation.
- Upon testing completion, delivering the fix to the customer involves a straightforward process of pushing the updated image to the production environment.

## Install Docker

Install Docker from the official website for your operating system from [here](https://docs.docker.com/get-docker/). Follow the instructions shown on the Docker website for your OS.

After the installation, use the following command to check Docker Version.

```
docker --version
```
Following output should be displayed with variation in version and build
>Docker version 24.0.7, build afdd53b

## Docker Image ('hello-world')

Run the following command in CLI
`docker run hello-world`

It should generate the following output:

> Unable to find image 'hello-world:latest' locally
> latest: Pulling from library/hello-world
> c1ec31eb5944: Pull complete
> Digest: sha256:4bd78111b6914a99dbc560e6a20eab57ff6655aea4a80c50b0c5491968cbc2e6
> Status: Downloaded newer image for hello-world:latest

> Hello from Docker!
> This message shows that your installation appears to be working correctly.

> To generate this message, Docker took the following steps:
    > 1. The Docker client contacted the Docker daemon.
    > 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    > (amd64)
    > 3. The Docker daemon created a new container from that image which runs the
    > executable that produces the output you are currently reading.
    > 4. The Docker daemon streamed that output to the Docker client, which sent > it to your terminal.

> To try something more ambitious, you can run an Ubuntu container with:
> $ docker run -it ubuntu bash

> Share images, automate workflows, and more with a free Docker ID:
> https://hub.docker.com/

> For more examples and ideas, visit:
> https://docs.docker.com/get-started/