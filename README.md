
## Run DB without password
```
docker run -d -p 27017:27017 -p 28017:28017 -e AUTH=no tutum/mongodb
```

## Run the API
```
npm run compile
```

```
npm start
```