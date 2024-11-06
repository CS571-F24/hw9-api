build
```bash
docker build . -t ctnelson1997/cs571-f24-hw9-api
docker push ctnelson1997/cs571-f24-hw9-api
```

run
```bash
docker pull ctnelson1997/cs571-f24-hw9-api
docker run --name=cs571_f24_hw9_api -d --restart=always -p 48109:48109 -v /cs571/f24/hw9:/cs571 ctnelson1997/cs571-f24-hw9-api
```

