# 윤훈의 GitHub Study
 ## Algorithm

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=gns6088)](https://solved.ac/profile/gns6088)


## Tech Stack

![Java](https://img.shields.io/badge/Java-17-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-Web%20Page%20Tech-FF6F00?style=for-the-badge&logo=coffeescript&logoColor=white)
![Servlet](https://img.shields.io/badge/Servlet-Java%20Web-6DB33F?style=for-the-badge&logo=apachetomcat&logoColor=white)
![JDBC](https://img.shields.io/badge/JDBC-Database%20Connectivity-336791?style=for-the-badge&logo=databricks&logoColor=white)
![React](https://img.shields.io/badge/React-19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Python](https://img.shields.io/badge/Python-Data%20Processing-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Modeling%20%26%20Query-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-System%20Programming-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-System%20Level-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-OOP%20Practice-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-.NET%20Study-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white)

## About Me

- Java와 웹 백엔드의 동작 원리를 직접 구현하면서 익히고 있습니다.
- Linux 환경에서 파일 처리, 프로세스, 시스템 호출 흐름을 실습하며 기초 체력을 쌓고 있습니다.
- Python으로 공공 데이터 수집, CSV 가공, 데이터 정리 자동화를 경험했습니다.
- React + Vite 기반 프론트엔드 구조도 함께 학습하며 화면과 데이터 흐름을 같이 보고 있습니다.
- SQL 모델링과 정규화 연습을 통해 데이터 설계 감각을 키우고 있습니다.

## What I Learned

### Java Backend

- Servlet, JSP, JDBC, MVC 패턴 구조 학습
- Request / Response 흐름, Forward / Redirect 차이 이해
- DAO / DTO 분리와 게시판, 회원, DB 연동 구조 연습
- Tomcat 기반 Java Web 프로젝트 구성 경험

관련 학습 정리:
- [java/Java_백엔드_학습정리.md](./java/Java_백엔드_학습정리.md)

### Linux System Programming

- 파일 및 디렉토리 처리
- `open`, `read`, `write`, `lseek`, `stat`, `chmod` 같은 저수준 시스템 호출 학습
- `ncurses`를 활용한 터미널 기반 시스템 모니터 구현
- 프로세스 목록, CPU/메모리 사용량 시각화 실습

관련 학습 정리:
- [linux/리눅스_파일처리_학습정리.md](./linux/리눅스_파일처리_학습정리.md)

### Python Data Work

- 공공 API 호출 후 데이터 수집
- `pandas` 기반 CSV / Excel 데이터 가공
- 문자열 분리, 컬럼 정리, 재료 데이터 전처리 경험

관련 파일:
- [python/2학년2학기/api.py](./python/2학년2학기/api.py)
- [python/2학년2학기/split_csv_by_comma.py](./python/2학년2학기/split_csv_by_comma.py)

### Frontend

- React 19 + Vite 개발 환경 구성
- 컴포넌트 구조와 상태 관리 기초 학습
- HTML / CSS 기반 이력서 및 포트폴리오 페이지 제작

관련 파일:
- [myApp/package.json](./myApp/package.json)
- [MyResume/index.html](./MyResume/index.html)

### Database / SQL

- MySQL 기반 테이블 설계 및 CRUD 학습
- 정규화, 관계 모델링, JDBC 연결 실습
- 수업 단위 SQL 스크립트 및 모델링 파일 정리

관련 파일:
- [sql/jdbcBackend.sql](./sql/jdbcBackend.sql)

## Featured Work

### 1. FoodPage

Java Servlet / JSP / MVC / JDBC 기반의 푸드 플랫폼 프로젝트입니다.  
레시피 조회, 재료 관리, 외부 API 연동, 마트 경로 탐색 같은 기능을 구현하며 웹 애플리케이션 구조를 실습했습니다.

핵심 포인트:
- MVC 패턴 기반 프로젝트 구조
- 식품안전나라 API, Kakao Local API, ODsay API 연동
- 레시피 상세 정보 파싱 및 조리 시간 추정 로직
- 냉장고 재료 비교 및 관리 기능

관련 문서:
- [FoodPage/README.md](./FoodPage/README.md)

### 2. Linux Monitor Practice

C와 `ncurses`를 사용해 터미널 기반 시스템 모니터를 구현했습니다.  
CPU, 메모리, 프로세스 상태를 출력하고 정렬, 선택, 시그널 전송까지 다루는 구조를 실습했습니다.

관련 파일:
- [linux/main.c](./linux/main.c)

## Study Keywords

`Java` `Servlet` `JSP` `JDBC` `MVC` `React` `Vite` `Python` `Pandas` `Linux` `C` `C++` `C#` `SQL` `MySQL` `Git`

## Goal

지금은 다양한 기술을 넓게 경험하면서도,  
특히 Java 백엔드와 Unity/C# 방향으로 더 깊게 성장할 수 있도록 학습 기록과 실습 결과를 꾸준히 쌓아가고 있습니다.

## Contact

- GitHub: [yunhoon0206](https://github.com/yunhoon0206)
- Email: [dbsgns6088@gmail.com](mailto:dbsgns6088@gmail.com)
