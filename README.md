
# Alpine C++ Docker Image
Building Image:
```
docker build -t alpinecpp .
```
If building from a Mac, buld with platform flag:
```
docker build --platform linux/amd64 -t alpinecpp .
```

Running Image:
```
docker run -it alpinecpp /bin/bash
```

Tagging Image:
```
docker tag alpinecpp:latest mali617/alpinecpp:1.0
```

Pushing Image:
```
docker push mali617/alpinecpp:1.0
```