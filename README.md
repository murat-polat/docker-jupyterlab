This repository designed to run Jupyter Notebook, JupyterHub and JupyterLab inside a Docker container.
That's come with  Pandas, Numpy, Bokeh, Plotly, Dash and other popular libraries.

JupyterHub has admin interface, JupyterLab has Jupyter Notebook, console, terminal, text editor and Jitsi video-meeting.



### Build your docker image

` git clone https://github.com/murat-polat/docker-jupyterlab `

` cd docker-jupyterlab `

` docker build -t <yourID>/jupyterlab .`

Make your own docker image and push to docker registry(DockerHub)
`docker login`

`docker push <yourID>/jupyterlab `


### Run JupyterLab/JupyterHub

` docker run --rm -p 8000:8000 -d <yourID>/jupyterlab:latest `

Then go to the:

http://localhost:8000 or  http://YourServerIP:8000

### How to use ?
JupyterHub admin Control Panel for add/remove JupyterLab users, start/stopp servers and access to others common_users server and notebooks.
##### JupyterHub Control Panel

![](/src/adminPanel.png)


##### JupyterLab

JupyterLab is next-generations, great advanced tools for everyone. Not just a Jupyter Notebook,that comes with text editor, console, terminal, Jitsi-Meet and much more. For more information please visit https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html

![](/src/Lab.png)




