# ipfs.io, dweb.link은 느립니다

나만의 ipfs http gateway 단독서버를 쓰세요.

# 실행 조건

- docker
- docker hub desktop (선택)


## docker-compose를 이용해서 배포하세요

1.이 레포지토리를 clone하세요
```bash
git clone https://github.com/ketrelhf/ipfs-gateway-docker.git
```
2.nginx 설정 수정하기
reverse-proxy/data/gateway.conf 파일을 수정하고,
https(443) 서버를 여실려면, certs 폴더를 만들고 SSL 키파일을 넣으세요.

3.폴더에 진입하고, 빌드/실행하세요
```bash
cd ipfs-gateway-docker
docker-compose up
```


