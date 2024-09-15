# nginx-docker-certbot

Configuration files for deployment fullstack applications 

First of all you need to move here your `backend` and `frontend` applications folders with `Dockerfile` inside in

### First Step
```bash
docker compose up -d --build
# Here we actually running our nginx server without ssl sertification
```

### Second Step
```bash
chmod +x init-letsencrypt.sh
# Giving acces to run 

./init-letsencrypt.sh
# Run
```

### Third Step

After completing two steps, we must to uncomment ssl server config inside `/data/nginx/` `app.conf`

### Here we are
```bash
docker compose up --build
# add -d flag to run it in backround
```
