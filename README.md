# hello world docker
Docker image with React project

Step 1. Download the project from this repository, it contains the React app and the dockerfiles necessary to create the docker image.

Step 2. Inside the project's folder in the command prompt use the next command: docker build -t helloworld:latest .
        This command will create the docker image reading the dockerfile and executing its steps(include the dot after latest).
        
Step 3. Once the process is finished, use this command: docker run --name hello -d -p 7775:7775 helloworld:latest
        It will create a container with the image already created, and deploy it in localhost:7775 (supposedly).

Once the container is created, you can search into and find a folder(workdir) named /Mancilla_Francisco_site with the project files.

Uploading the image was impossible because it weights over 1GB(and its only a hello world).
