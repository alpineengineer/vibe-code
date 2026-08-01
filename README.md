I'm still dorking around with this project. Below are the cmds to build and run the docker container. 


Build the Docker Image
Open a terminal in the vibe-coding folder and run:

docker build -t vibe-coding-login .
Run the Container
docker run --rm --name vibe-coding-login-container -p 8080:80 vibe-coding-login
Then open this address in a browser:

http://localhost:8080
Stop the Container
Press Ctrl+C in the terminal where the container is running.

You can also stop it from another terminal with:

docker stop vibe-coding-login-container
