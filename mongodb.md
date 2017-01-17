# MongoDB

Running a MongoDB instance locally, while storing the MongoDB data in a Docker volume:

```
docker run -it --rm -p 27017:27017 -v ~/data/mongo:/data/db mongo:3.2
```
