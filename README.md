# How to use
1. git clone
2. Build
3. Launch container
4. Create vue project
5. Start local server
6. Check your URL

# git clone

# Build
```
prompt % docker-compose build
```

# Launch container
```
prompt % docker-compose up -d
```

# Create vue project
```
prompt % docker-compose exec app /bin/sh
```

```
/usr/src/app # vue create .
```

# Start local server
```
/usr/src/app # npm run serve
```

# Check your URL
default URL is http://localhost:9050/

