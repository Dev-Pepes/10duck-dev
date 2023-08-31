# 10duck-dev

## 필수 작업

1. Repository Clone && cd `10duck-dev`
2. `git submodule update --remote`
3. `git submodule update --init --recursive`

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
