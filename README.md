<!-- # 프로젝트 WIWY -->

# WIWY(Covid-19 통계 및 커뮤니티 제공 서비스)

## Prerequisites
- Docker > 19.x

## Installation
1. 소스코드 다운로드 - WIWY 클론 후 해당 디렉토리에서 서브 모듈 server, client 클론 진행
    ```shell
    $ git clone https://github.com/W-I-W-Y/WIWY.git
    $ cd WIWY
    WIWY$ git clone https://github.com/W-I-W-Y/client.git
    WIWY$ git clone https://github.com/W-I-W-Y/server.git
    ```
    or
    ```shell
    $ git clone https://github.com/W-I-W-Y/WIWY.git
    $ cd WIWY
    $ git submodule init
    $ git submodule update
    ```
    
2. 리액트 npm 패키지 설치
    ```shell
    $ cd client
    client$ npm install
    ```
3. 스프링부트 gradle 빌드
    ```shell
    $ cd server
    server$ ./gradlew build
    ```
# Usage
- 도커 이미지 빌드 및 컨테이너 실행
    ```shell
    $ docker-compose up --build
    ```
- 컨테이너 실행
    ```shell
    $ docker-compose up
    ```
- 컨테이너 다운
    ```shell
    $ docker-compose down
    ```
