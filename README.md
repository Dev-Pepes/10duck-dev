# 10duck-dev

## 필수 작업

1. Repository Clone && cd `10duck-dev`
2. Submodule 정보 갱신
   1. `git clone --recurse-submodules https://github.com/Dev-Pepes/playlist_be.git`
   2. `git clone --recurse-submodules https://github.com/Dev-Pepes/playlist_fe.git`
   3. `git clone --recurse-submodules https://github.com/Dev-Pepes/10duck-config.git`

### 프로젝트별 필요 작업

#### 10duck-config

- Local의 resource에 파일로 제공받은 application.yml추가

#### playlist_fe

1. mkdir playlist_fe/env
2. 공유받은 .env.{label} 추가

#### playlist_be

> 작업 필요 X

## 실행방법

- `docker-compose up -d`
- 10duck-config가 실행되야함.

### Redis

SET watermelon 15000
GET watermelon

실행 : `docker-compose up -d`  
`docker-compose down`  
`docker exec -it redis_10duck redis-cli`

docker build -t config . --platform linux/x86_64
