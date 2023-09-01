# docker_hub
Process of pushing and pulling images to Docker Hub


   
-  Login docker
```   
docker login
```

- 도커 이미지 목록 확인
```
$ docker images
```

- 도커 컨테이너를 이미지로 생성
```
$ docker commit -m "commit message" container_name container_name:latest
```

- 도커 허브에 올릴 이미지 이름 변경
 ```
$ docker tag [pastname:tag]/[newname:tag]
```

- 도커 이미지 push
```
$ docker push [username]/[repository_name]:tagname
```

- 도커 이미지 pull
```
$ docker pull [username]/[repository_name]:tagname
```
