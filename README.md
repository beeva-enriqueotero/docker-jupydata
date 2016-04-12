# docker-jupydata
**Docker**ized (Minimal: &lt;1GB) **ju**pyter notebook for **py**thonic **data** science

#### Quick start
- Install Docker: 

`sudo apt-get install docker.io` in Ubuntu

- Run the container:

`docker run -it -p 8888:8888 -v "$(pwd):/notebooks" beevaenriqueotero/docker-jupydata`

- And browse *http://localhost:8888*
