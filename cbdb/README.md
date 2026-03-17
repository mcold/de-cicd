# Install Apache Cloudberry With Docker

Appropriate only for Linux

> Deploy

```shell
docker compose up
```

**Starting DB**

Should start by itself
If not do the next step:

```shell
docker exec -it cbdb-cdw /bin/bash

[gpadmin@cdw /] gpstart -a
```


**Connect**

db/login/password: gpadmin