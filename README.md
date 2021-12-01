# OpenHIM Common

1. Edit the `default.json` file to point to the **public** host and port of your server. If you are just testing on localhost you can leave it set at the defaults.

2. Spin up the OpenHIM core and console easily with docker compose:

3. Generate the cert files and update the cert files path in conf/nginx/openhim.template  

4. start the compose
```
docker-compose build && docker-compose up -d
```

5. Access on https://localhost or at https://<your_server>

6. Access API on https://localhost/api or at https://<your_server>/api

7. Send traffic to mediator https://localhost/queue or at https://<your_server>/queue
