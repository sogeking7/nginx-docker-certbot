# nginx-docker-certbot

Configuration files for deployment fullstack applications 

First of all you need to move here your `backend` and `frontend` applications folders with `Dockerfile` inside in

### First Step
```
./init-letsencrypt.sh
```

### Second Step
```bash
docker compose up --build
# add -d flag to run it in backround
```
