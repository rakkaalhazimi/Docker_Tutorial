# Build Docker Image
```
docker build -t flask:test .
```

# Run Docker Container
```
docker run -it --rm -p 5000:5000 flask:test
```