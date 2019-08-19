```
docker build -t dotnetapp .
docker run --rm dotnetapp
```

```
docker build --pull -t aspnetapp .
docker run --name aspnetcore_sample --rm -it -p 8000:80 aspnetapp
```