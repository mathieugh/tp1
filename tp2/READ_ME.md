# To start an instance of elasticsearch

```
docker-compose up
```

# To scale the instances of elasticsearch

```
docker-compse up --scale elasticsearch=2
```

# To find port 
```
docker-compose ps
```

# To stop elasticsearch

```
docker-compose down
```

# To remove image
```
docker image remove IMAGE
```
ou encore 
```
docker-compose down --rmi local
```