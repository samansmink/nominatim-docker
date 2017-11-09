How to use
===
1. Open terminal


2. Clone repository

  ```
  # git clone git@github.com:samansmink/nominatim-docker.git
  # cd nominatim-docker/2.5
  ```

3. Build 

  ```
  docker build -t nominatim .
  ```
4. Run

  ```
  docker run --restart=always -d -p 8080:8080 --name nominatim-netherlands nominatim
  ```
  If this succeeds, open [http://localhost:8080/](http:/localhost:8080) in a web browser



Forked from https://github.com/mediagis/nominatim-docker
