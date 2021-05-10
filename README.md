# Docker Image For Run Firefox via GUI of Host System
This Docker Image is for Launching Docker container which contains the firefox GUI 
<br>
## How to use?
- Pull the Docker image by command
  ```
  docker pull geekgodgagan/docker_firefox_gui:v1
  ```
- Run command to launch Firefox
  ```
  docker container run -it --env="DISPLAY" --net=host geekgodgagan/docker_firefox_gui:v1
  ```
- Then finally you get like this
<img height = "250" width = "600" src="https://github.com/geekgodgagan/docker_firefox_gui/blob/main/firefox.jpg"/>
