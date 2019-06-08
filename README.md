# Waterfall

"鲜天下" 平台


## Prerequisite

- `docker : >= 18.09.6`
- `docker-compose : >= 1.8`

## How to deploy

You can deploy the frontend, the backend and the database with just three command. 

```
git clone https://github.com/wwyf/Waterfall
cd Waterfall
docker-compose up -d
```

Then, the port 80 will be exposed to the port which docker selects. You can find it with `docker ps`.