## 프로젝트명: Chi Chu🦷

![사이트 소개 이미지](https://user-images.githubusercontent.com/56299114/169871127-de95efcd-9d57-4d92-bb10-4e0e042aed22.png)

`빅데이터 치아 보험 추천 서비스`

 __Chi Chu란?__

'치'아보험 '추'천 서비스를 줄여서 만든 서비스 명.

#### 👆클릭 시 Chi Chu 소개 UCC 영상으로 이동!

[![잠시만요](https://user-images.githubusercontent.com/56299114/169869838-92a86c6f-d7d9-4d2c-ba3a-b72c15653d53.gif)](https://www.youtube.com/watch?v=PecaFVn66D8)



## 🌈프로젝트 개요

**약 37만 개의 보험계약 빅데이터**를 기반으로 빠르고 정확하게 치아보험을 추천해주는 
빅데이터 기반 치아보험 추천 서비스, **Chi Chu!**



#### 💫Tech Stacks & IDE ####



#### 📅프로젝트 기간 ####

- 2022.02.21 ~ 2022.04.08  



### 0. 랜딩 페이지

- 스크롤을 내려 맨 위부터 아래까지 치츄 서비스 정보 흝어보기 

![치츄메인](https://user-images.githubusercontent.com/56299114/169867005-41b705de-1ab4-4b0a-943b-5545b32fe9fe.gif)

### 1. 보험 검색

- 랜딩페이지에서 버튼을 눌러서 검색 페이지로 이동
- 성별과 생년월일을 작성하는 부분
- 보험 나이 툴팁에 호버해서 보험나이 설명 확인

![치츄검색](https://user-images.githubusercontent.com/56299114/169866835-75a07678-1cfe-44f6-bbb9-3e346562f84f.gif)

### 2. 검색 결과 페이지

- 결과로 나온 보험 카드들 보여주기
- 치츄지수순, 보험료 낮은 순, 보장 많은 순으로 정렬된 검색 결과 확인 가능.
- 검색 결과 더 보기

![정렬및결과더보기](https://user-images.githubusercontent.com/56299114/169866349-eda30e18-2133-49ef-937b-e9ec5930a339.gif)

- 2차 검색으로 담보와 납입 보험료를 조절해 필요한 보험을 찾을 수 있음.

- 검색결과에서 성별.연령.납입기간.보험기간을 다르게 설정해 다시 검색할 수 있음.

  ![치츄상세검색](https://user-images.githubusercontent.com/56299114/169867156-dfd3f5da-7738-47bb-8f70-e75af434ef14.gif)



- 맨 밑에는 나와 비슷한 연령.성별의 이용자가 많이 가입한 보험 & 보험료 대비 보장금액 높아 가성비 좋은 보험 추천.

![하단추천](https://user-images.githubusercontent.com/56299114/169867178-66dbcd96-ab35-42c4-bfa1-38995abcbbde.gif)



### 3. 보험 상세페이지

- 해당 보험의 치츄지수가 어느 수준인지 확인
- 치츄지수를 구성하는 회사지수, 상품지수, 유저지수가 뭔지에 대한 설명

![보험상세페이지1](https://user-images.githubusercontent.com/56299114/169866302-a1f6bb34-af05-4be7-8b1e-6527f3435713.gif)

- 현재 내 나이와 성별, 보장기간에 맞는 보험 보여주고 사이트에 가서 가입가능.

- 보장내역과 치아보철치료, 보존치료, 신경치료, 기타에  적힌 설명 확인
- 그래프:보험가입자 연령분포, 주력보장치료 확인 가능

![보험상세페이지2](https://user-images.githubusercontent.com/56299114/169866312-991c8cac-64c4-4922-b867-a9ccd06425a1.gif)

### 4. 보험 비교

- 검색결과 페이지에서 3가지 보험 선택하여 모달에 띄움
- 비교 결과 보기를 통해 창에서 보험료와 치츄지수, 보철.보존.치수치료 보장금액 차이 확인.

![보험비교](https://user-images.githubusercontent.com/56299114/169866276-513736ee-73e6-4db2-be11-8a938d794bb9.gif)



### 5. 보험 팁

- 치아보험과 관련된 다양한 팁을 안내하는 카드뉴스

- ![보험tip페이지](https://user-images.githubusercontent.com/56299114/169867353-b4a8f543-7e53-4180-8cc6-182cea217d7e.gif)

  

- 카드로 구성된 담보가이드입니다. 어떤 상황에서 어떤 담보가 필요한 지 쉽게 알 수 있어요!

![보험tip](https://user-images.githubusercontent.com/56299114/169866222-e71d2e08-566f-4d48-831a-6fb144d39b7d.gif)

### AWS

```
웹 접속 주소 : http://j6d206.p.ssafy.io/
mobaxterm으로 접속 시 : ssh -i J6D204T.pem ubuntu@j6d206.p.ssafy.io
```



### MYSQL workbench 접속

```
mysql 'version': '8.0.28-0ubuntu0.20.04.3'

host : 'chichu@221.153.81.232'
user_name : chichu
user_password : ssafy
port : 3306
```



### 라이브러리 설치, 코드 실행

```
[back build] 
/S06P22D206/back
$ pip install -r requirements.txt
/S06P22D206/back/chichu
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py runserver


[front build]
/S06P22D206/frontend
$ npm i 
$ npm start
```



### jenkins <=> gitlab

```
[jenkins]
주소 : http://j6d206.p.ssafy.io:9090/
- id : chichu
- pw : ssafy
- token : 729482e3c7a0000401f32fecf080e172

[gitlab]
- gitlab webhook : http://j6d206.p.ssafy.io:9090/project/chichu
- gitlab token : RrGRjYjnXr9XxUexxUE3
```



### nginx_proxy 설정

#### nginx.conf

```
user nginx; 
worker_processes auto; 
worker_priority 0; 

error_log /var/log/nginx/error.log notice;
pid /var/run/nginx.pid;

events {
	worker_connections 1024; ## Default: 1024, 현 서버는 RAM 8GB라 상향조정
}

http {
    include /etc/nginx/mime.types;
    default_type application/octet-stream;
    log_format main '$remote_addr - $remote_user [$time_local] "$request" '
                    '$status $body_bytes_sent "$http_referer" '
                    '"$http_user_agent" "$http_x_forwarded_for"';
    
    access_log /var/log/nginx/access.log main;
    
    sendfile on;
    keepalive_timeout 65;
    server_tokens off;
    
    upstream frontend {
        server front:3000;
        keepalive 32;
    }    
    
    upstream backend {
        server back:8000;
        keepalive 32;
    }
    
    include /etc/nginx/conf.d/*.conf;
}

```



#### nginx/conf.d/default.conf

```
server {
    listen 80;
    listen [::]:80;
    server_name j6d206.p.ssafy.io;

    #access_log /var/log/nginx/host.access.log main;

    location / {
        proxy_pass http://frontend;
    }

    location /api/ {
        proxy_pass http://backend;
    }

    #error_page 404 /404.html;
    # redirect server error pages to the static page /50x.html
    #

    error_page 500 502 503 504 /50x.html;
    location = /50x.html {
        root /usr/share/nginx/html;
    }

}
```



### DB 덤프파일 설치

```none
sudo mysqldump  -h 127.0.0.1 --user=chichu -p --all-databases > all_databases.sql
```





