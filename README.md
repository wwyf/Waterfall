# Waterfall

"鲜天下" 平台

## How to deploy

You can deploy the frontend, the backend and the database with just three command. 

```
git clone https://github.com/wwyf/Waterfall
cd Waterfall
docker-compose up -d
```

Then, the port 80 will be exposed to the port which docker selects. You can find it with `docker ps`.