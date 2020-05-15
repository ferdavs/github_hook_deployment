# github_hook_deployment
Using github's webhook to automatically deploy this repo

## required:

- GITHUB_SECRET 

- REPO_PATH /opt/github_deploy
## Install dependencies

`$ pip install -r requirements.txt`

## Run the application

`$ gunicorn --bind 0.0.0.0 wsgi:application --reload`
