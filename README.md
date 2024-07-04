# Simple Flask with Docker Application#


Build the image using the following command

```bash
$ docker build -t flask-docker-app .
```
Run the Docker container using the command shown below.

```bash
$ docker run -d -p 5000:5000 flask-docker-app
```

The application will be accessible at http://localhost:5000/
