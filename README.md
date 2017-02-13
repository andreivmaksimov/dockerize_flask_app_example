# Dockerizing Simple Flask App

This project is a simple application. Blog post can be found [here](http://bit.ly/2jACRpJ).

```
docker build -t dockerize_flask_app_example:v0.1 . 
docker run -d -p 5000:5000 dockerize_flask_app_example:v0.1
```
