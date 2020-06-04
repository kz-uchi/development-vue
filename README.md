# development-vue
Create Development Environment of Vue.js Application on Docker.


## How to use
1. git clone
2. Build
3. Launch container
4. Create vue project
5. Start local server
6. Check your URL

## git clone
Please git clone or Download this repository.

## Build
```
prompt % docker-compose build
```

## Launch container
```
prompt % docker-compose up -d
```

## Create vue project
```
prompt % docker-compose exec app /bin/sh
```

```
/usr/src/app # vue create .
```

Vue Environment is omitted.


## Start local server
```
/usr/src/app # npm run serve
```

## Check your URL
Default URL is http://localhost:9050/

