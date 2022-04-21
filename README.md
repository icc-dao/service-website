#Dockerized: ICCD website + blog

Execute:
```
sudo chown -R 33:33 plugins
find plugins  -type d -exec sudo chmod 0755 {} \; &
find plugins  -type f -exec sudo chmod 0644 {} \; &
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d --build
```

Default Login after Import:
```
User: OliverH1
Pass: mF!tIVb@^N44)skkfC
```