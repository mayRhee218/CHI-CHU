## 🦷프로젝트명: Chi Chu


![사이트 소개 이미지](https://user-images.githubusercontent.com/56299114/169871127-de95efcd-9d57-4d92-bb10-4e0e042aed22.png)

`빅데이터 치아 보험 추천 서비스`

 __Chi Chu란?__

'치'아보험 '추'천 서비스를 줄여서 만든 서비스 명.

#### 👆클릭 시 Chi Chu 소개 UCC 영상으로 이동!

[![잠시만요](https://user-images.githubusercontent.com/56299114/169869838-92a86c6f-d7d9-4d2c-ba3a-b72c15653d53.gif)](https://www.youtube.com/watch?v=PecaFVn66D8)



## 🌈프로젝트 개요

- **약 37만 개의 보험계약 빅데이터**를 기반으로 빠르고 정확하게 치아보험을 추천해주는 
  빅데이터 기반 치아보험 추천 서비스, **Chi Chu!**

- 한국신용정보원이 제공하는 **개인신용표본 모의 DB 5만 명 사용자 정보, 보험 계약 정보 데이터**를 바탕으로 **연령, 성별, 보험종류(카테고리), 월 납입 희망금액, 담보(세부보장사항), 보장금액**에 따라 보험을 추천해준다.
  

#### 💫Tech Stacks & IDE ####

**Frontend**

- <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" style="zoom:80%;" /><img src ="https://img.shields.io/badge/TypeScript-3178C6.svg?&style=for-the-badge&logo=TypeScript&logoColor=white" alt="TypeScript" style="zoom:80%;"/><img src="https://img.shields.io/badge/Recoil-003545?style=for-the-badge&logoColor=white" alt="MariaDB" style="zoom:80%;" />
- <img src="https://img.shields.io/badge/styled_components-#DB7093.svg?style=for-the-badge&logo=styled-components&logoColor=black" alt="styled_components" style="zoom:80%;" /><img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" style="zoom:80%;" /><img src="https://img.shields.io/badge/Chart.js-#FF6384.svg?style=for-the-badge&logo=Chart.js&logoColor=black" alt="Chart.js" style="zoom:80%;" />

**Backend**

- <img alt="Python" src ="https://img.shields.io/badge/Python-3776AB.svg?&style=for-the-badge&logo=Python&logoColor=white" style="zoom:80%;"/><img alt="Django" src ="https://img.shields.io/badge/Django-#092E20.svg?&style=for-the-badge&logo=Django&logoColor=white" style="zoom:80%;"/><img alt="MySQL" src ="https://img.shields.io/badge/MySQL-#4479A1.svg?&style=for-the-badge&logo=MySQL&logoColor=white" style="zoom:80%;"/><img alt="Swagger" src ="https://img.shields.io/badge/Swagger-#85EA2D.svg?&style=for-the-badge&logo=Swagger&logoColor=white" style="zoom:80%;"/>
- <img alt="Docker" src ="https://img.shields.io/badge/Docker-#2496ED.svg?&style=for-the-badge&logo=Docker&logoColor=black" style="zoom:80%;"/><img alt="NGINX" src ="https://img.shields.io/badge/NGINX-#009639.svg?&style=for-the-badge&logo=NGINX&logoColor=black" style="zoom:80%;"/><img alt="Jenkins" src ="https://img.shields.io/badge/Jenkins-#D24939.svg?&style=for-the-badge&logo=Jenkins&logoColor=black" style="zoom:80%;"/>

**Big Data Analysis**

- <img alt="pandas" src ="https://img.shields.io/badge/pandas-#150458.svg?&style=for-the-badge&logo=pandas&logoColor=white" style="zoom:80%;"/><img alt="Jupyter" src ="https://img.shields.io/badge/Jupyter-#F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" style="zoom:80%;"/>



#### 📅프로젝트 기간 ####

- 2022.02.21 ~ 2022.04.08  

#### :bar_chart:데이터셋

금융빅데이터개방시스템(https://credb.kcredit.or.kr:3446/frt/main.do)에서 제공된 모의 DB(사용자 정보 약 5만 명) 중 **차주정보,보험계약정보, 보험담보정보**.

- **차주정보: 5만명 차주**에 대한 **id, 연령, 성별**

![차주정보](https://user-images.githubusercontent.com/56299114/170535418-c1e2e2a5-0844-48cc-a88d-856e75ad66c2.png)

- **보험계약정보: 납입주기, 납입금액, 보험계약기간, 보험종류 등**

![보험계약정보](https://user-images.githubusercontent.com/56299114/170535473-25ba0bf9-7e1f-4f3d-9f80-4d6761419095.png)

- **보험담보정보: 보험계약의 세부담보 코드** 및 **금액** 포함

```json
💡담보란?
보험 상품 가입을 위해 선택할 수 있는 **개별 계약 내용**을 의미합니다. 
일반적으로 ‘암보험’이 라고 표현하는 상품에는 ‘암 진단비’, ‘암 입원 일당’, ‘암 사망’ 등 
암 발병 후 사고 처리를 위한 **개별 담보**를 선택할 수 있습니다. 
암 진단비는 ‘약관에서 정하는 암 진단을 받으면 보험금을 받을 수 있는 담보’를 뜻하는 것으로, 
**계약 시 해당 담보를 선택하지 않았다면 사고 후 관련 보험금을 받을 수 없습니다.** 
따라서, 담보 구성은 보험 상품에서 우리가 선택할 수 있는 개별 계약 옵션 설계를 통해 
선택한 결과를 의미합니다.
```

![보험담보정보](https://user-images.githubusercontent.com/56299114/170535478-809869b9-004a-41db-abb9-c5c586b6c2d7.png)
![보험코드](https://user-images.githubusercontent.com/56299114/170535487-488bb326-ef17-407f-911f-1429dfa6613f.png)

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

