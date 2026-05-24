### What is the difference between:

#### ▪ CMD & ENTRYPOINT

- **CMD:** To configure the container as an executable  
- **ENTRYPOINT:** To provide default commands or arguments  

#### ▪ COPY & ADD

- **COPY:** Copies new files or directories to container  
- **ADD:** Includes extra features like downloading from URLs and automatically extracting compressed archives  

---

# Problem 1

### Tasks

- Run the container `hello-world`
- Check the container status
- Start the stopped container
- Remove the container
- Remove the image

![Problem 1 - Step 1](Images/p11.png)

![Problem 1 - Step 2](Images/p12.png)

![Problem 1 - Step 3](Images/p13.png)

![Problem 1 - Step 4](Images/p14.png)
---

# Problem 2

### Tasks

- Run container `centos` or `ubuntu` in an interactive mode
- Run the following command in the container:

```bash
echo docker
```

- Open a bash shell in the container and touch a file named `hello-docker`
- Stop the container and remove it. Write your comment about the file `hello-docker`
- Remove all stopped containers

![Problem 2 - Step 1](Images/p21.png)

![Problem 2 - Step 2](Images/p22.png)

![Problem 2 - Step 3](Images/p23.png)

![Problem 2 - Step 4](Images/p24.png)

---

# Problem 3

### Tasks

- Deploy a MySQL database called `app-database`
- Use the `mysql:latest` image
- Use the `-e` flag to set:

```text
MYSQL_ROOT_PASSWORD=
```

- Run the container in the background

![Problem 3](Images/p31.png)

---

# Problem 4

### Tasks

- Run the image `Nginx`
- Add HTML static files to the container and make sure they are accessible
- Commit the container with image name `IMAGE_NAME`

![Problem 4 - Step 1](Images/p41.png)

![Problem 4 - Step 2](Images/p42.png)

![Problem 4 - Step 3](Images/p43.png)

![Problem 4 - Step 4](Images/p44.png)

---

# Problem 5

### Tasks

- Create a simple Python app
- Create a Dockerfile to containerize the Python app
- Build the image and test it
- **(Bonus)** Create a Dockerfile for the same app in smaller size using multi staging
- Push the created image into your Docker Hub repo

![Problem 5 - Step 1](Images/p51.png)

![Problem 5 - Step 2](Images/p52.png)

![Problem 5 - Step 3](Images/p53.png)

![Problem 5 - Step 4](Images/p54.png)

![Problem 5 - Step 5](Images/p55.png)

![Problem 5 - Step 6](Images/p56.png)

![Problem 5 - Step 7](Images/p57.png)

![Problem 5 - Step 8](Images/p58.png)

![Problem 5 - Step 9](Images/p59.png)

