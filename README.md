# Usage
### set up


```
※Before install docker for mac

$ docker-compose build
$ docker-compose up

# Quit or Open another window
$ docker-compose run web rails db:create
$ docker-compose run web rails db:migrate
```

### access
http://0.0.0.0:3000


### If you want to attach container


```
$ docker-compose exec web bash
```
