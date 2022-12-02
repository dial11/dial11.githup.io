# Today I Learned (TIL)
<br>   

## 사전 학습   
 * **[js기초](./js기초.md)(혼.공.스)**
 * **[CS특강](./CS특강.md)**

### 2022.11.14   
 * **[git & github 특강](./git&Github특강.md)**
 * **[첫 미니 프로젝트](./첫프로젝트/첫_미니_프로젝트.md)**

### 2022.11.15
 * **[첫 미니 프로젝트](./첫프로젝트/첫_미니_프로젝트.md)**
 * 미니 프로젝트에 필요한 웹개발 복습
   
### 2022.11.16
 * **[첫 미니 프로젝트](./첫프로젝트/첫_미니_프로젝트.md)**
 * 미니 프로젝트에 필요한 웹개발 복습

### 2022.11.17
 * **[첫 미니 프로젝트](./첫프로젝트/첫_미니_프로젝트.md)**
 * 미니 프로젝트에 필요한 git 활용법 공부
 * githup 
    + 하나의저장소로 협업하기 위해 Pull requests사용

### 2022.11.18
 * **[첫 미니 프로젝트](./첫프로젝트/첫_미니_프로젝트.md)**
 * 내가 만든 페이지 코드 정리
 * 프로젝트 발표
 * **[CS특강](./CS특강.md)**

### 2022.11.21
 * 파이썬 문법 강의
   + if, else와 elif
     - 조건을 만족하지 않을 때 다른 코드를 실행하고 싶을 때
     - 다양한 조건을 판단할 때는 elif
   + 튜플 (tuple)
     - 리스트와 비슷하지만 불변
   + 집합 (set)
     - 중복이 제거
     - 교집합 / 합집합 / 차집합
   + f-string
   ```
   for s in scores:
       name = s['name']
       score = str(s['score'])
       print(f'{name}은 {score}점입니다')
   ```
   + try - except 문
     - 에러가 있어도 건너뛰게 할 수 있는 방법
     - 실제 프로젝트 남용하는 것은 금물 어디서 에러가 났는지 알 수 없음
   + 파일 불러오기
     - 다른 파일의 함수를 그래로 사용가능
       from main_func import *
     
(https://www.notion.so/dfb89a042c6f4b29b64ea4da03a37ea6#71e4bb75e0844d56b32a5e01b157f632)

### 2022.11.22 ~ 25
  * **[자료구조 알고리즘](./자료구조알고리즘.md)**
  * javascript 올인원
  * CS특강
     - https://teamsparta.notion.site/HTTP-HTTPS-f27bad886a4c4cf1932384f41cd77b67
     
### 2022.11.30
  * DB설계, 구축, mysql 특강
    - https://teamsparta.notion.site/11-30-DB-mysql-c193376d347943d8aaa33fbf0d52348a
```
데이터의 집합
DBMS
  - 데이터베이스를 관리하고 운영하는 소프트웨어
  - 계층형 DBMS
  - 망형 DBMS
  - 관계형 DMBS
     - 관계형 DBMS(Relational DBMS)는 줄여서 RDBMS라고 부릅니다. MySQL뿐만 아니라, 대부분의 DBMS가 RDBMS 형태로 사용됩니다. RDBMS의 데이터베이스는 테이블(table)이라는 최소 단위        로 구성되며, 이 테이블은 하나 이상의 열(column)과 행(row)으로 이루어져 있습니다.
SQL: DBMS에서 사용하는 언어
  - 데이터를 엑셀과 같이 정해진 틀(데이터 스키마)에 따라 테이블에 저장
```
  * 데이터베이스 설계
     - 1. 요구조건 분석
     - 2. 개념적 모델링
        - https://drive.google.com/file/d/1fpKnZw_HbMybaCXmYvPOBPLD5MrJEdZl/view
     - 3. 논리적 모델링
        - erd를 바탕으로 테이블 만들기
        -  ![11schema](https://user-images.githubusercontent.com/117889461/204723619-00e0f413-5502-4318-960d-9beb2c740d46.PNG)
     - 4. 물리적 모델링
        - 관계 스키마 모델의 물리적 구조를 정의하고 구현하는 과정 
  * 정규화(Normalization)
     - 중복 데이터를 없애고 관계를 단순하게 가져 간다
     - 제2정규화: 완전 함수적 종속 (부분 종속 제거)
       - 종속되는 요소가 많으면 그 종속되는 요소를 분리해야 된다

### 2022.12.01
  * RESTful API CS 특강
     - https://teamsparta.notion.site/12-1-RESTful-API-CS-083aa0cbcbb449edbbc3012215c73fad
  * html, css, javascript 특강
     - https://teamsparta.notion.site/12-01-html-css-javascript-939a3adb059541aeaa96c6aec9bf01e1

### 2022.12.02
  * S.A제작  
    - https://velog.io/@mad/%EB%89%B4%EC%8A%A4%ED%94%BC%EB%93%9C-%EB%AF%B8%EB%8B%88-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8
    - API, 역할 분담 ...
  * osi 7계층 특강
    - https://teamsparta.notion.site/osi-7-03d065a960704b4ca524c4a2d69ded2e
