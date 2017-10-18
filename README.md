# OpenHIM Common

1. Edit the `default.json` file to point to the **public** domain and port of your server. If you are jsut testing on localhost you can leave it set at the defaults, jsut remove the comments.

2. Spin up the OpenHIM core and console easily with docker compose:

```
docker-compose build && docker-compose up -d
```

3. Access on localhost:9000 or at <your_server>:9000
