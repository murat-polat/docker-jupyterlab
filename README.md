### Build your docker image

` git clone https://github.com/murat-polat/docker-jupyterlab `

` cd docker-jupyterlab `

` docker build -t <yourID>/jupyterlab .`

Make your own docker image and push to docker registry(DockerHub)
`docker login`

`docker push <yourID>/jupyterlab `


### Run JupyterLab/JupyterHub

` docker run --rm -p 8000:8000 -d <yourID>/jupyterlab:latest `
http://localhost:8000 or  http://YourServerIP:8000

### How to use ?
JupyterHub admin Control Panel for add/remove JupyterLab users, start/stopp servers and access to others common_users server and notebooks.
##### JupyterHub Control Panel

![](/src/adminPanel.png)


##### JupyterLab


![](/src/lab.png)




