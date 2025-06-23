## DJANGO CELERY POC


Usually I use pipenv, this project was built on Windows, but, as expected it can be run using docker

$ docker-compose up -d --build


django localhost -> localhost:8001

$ chmod +x dcelery/entrypoint.sh

Always check your local user is configured properly.

For just one repo, go into to the relevant repo DIR and:

git config user.name "Your Name Here"
git config user.email your@email.example

For (global) default email (which is configured in your ~/.gitconfig):

git config --global user.name "Your Name Here"
git config --global user.email your@email.example