# how to seup
```
# execute in this directory.
$ docker-compose up --build
```

# how to connect db
```
$ psql -h db_container -U $POSTGRES_USER -p $POSTGRES_PASSWORD
```

# how to setup nginx conf.
you modifiyed default.conf in this directory.

# how to login container
```
$ docker exec -it <container_id> bash
```

# you want to set db config or api config
# you set environment variable to .entv

