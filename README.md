# https://decompany.io Dockerizing


## 이미지 빌드하기

```
docker build -t decompanyio .
```

## 생성된 이미지 실행하기

```
docker run --rm -d -p 80:80 decompanyio
```