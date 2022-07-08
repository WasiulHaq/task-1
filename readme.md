* Run the docker compose up from the Jenkinsfile directory
`docker compose up -d`
* Develop the laravel appliction under the src directory
* Build the new image from Dockerfile under build directory
`docker build -t username/reponame:tag`
* Login Docker hub and push the new image to Docker hub
~~~
docker login
docker push <hub-user>/<repo-name>:<tag>
~~~
