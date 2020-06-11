![Django from scratch](https://github.com/devopsfied/devopsfied-django/blob/master/blob/django_icon.png?raw=true)

# Deploy Django app from scratch on AWS in just one step

Run and deploy Django app with devopsfied. 

<a href="https://devopsfied.com/download" target="_blank"><img src="https://github.com/devopsfied/devopsfied-django/blob/master/blob/download.jpg?raw=true" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/devopsfied/devopsfied-django.git

# cd into the django app
cd devopsfied-django
```

## Run the app

```bash
# Run django as you would normally
python manage.py runserver 0.0.0.0:8000
```

## Check it out

Visit your app at <a href="http://0.0.0.0:8000" target="\_blank">0.0.0.0:8000</a>

## Explore

With Devopsfied, you don't have to have anything installed on your machine to deploy your app:

```bash
# Deploy django web app in production using containers on EC2.
# Creates vpc, sg, subnet, ig, nat, alb, routes etc in aws in one step.

ds web app deploy app-ec2.yaml


# Deploy django web app in production using containers on ECS.
# Creates ecs cluster, tasks, vpc, sg, subnet, ig, nat, alb, routes etc in aws in one step.
ds web app deploy app-ecs.yaml

```

## Now What?
For more details about running django apps with devopsfied visit [guides.devopsfied.com/python/django/](https://guides.devopsfied.com/python/django/)

<a href="https://devopsfied.com"><img src="https://devopsfied.com/Devopsfied_files/favicon.ico" /></a>