# dockerText

docker 정리

-- httpd --
docker run --name ws2 -p 8081:80 httpd
docker exec ws2 /bin/sh

/usr/local/apache2/htdocs/

index.html 파일 수정 k

mac 에서 docker 커맨드 안될때 
https://nomadyoung-agency.tistory.com/33

docker compose
https://gist.github.com/egoing/b62aa16573dd5c7c5da51fd429a5faa2
docker-compose up
docker-compose down

docker commit "컨테이너 이름" "만들 컨테이너 이름"

https://www.44bits.io/ko/post/building-docker-image-basic-commit-diff-and-dockerfile#%EB%93%A4%EC%96%B4%EA%B0%80%EB%A9%B0


docker login

docker build -t web-server-build .
docker rm --force web-server
docker run -p 8888:8000 --name web-server web-server-build


echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin

vim ~/.zshrc 
export CR_PAT=YOUR_TOKEN 저장 
source ~/.zshrc 바로 실행

commit - back up
build - 이미지 만듬
push , pull
compose



github packages container registry 


# dockerText

# dockerText
