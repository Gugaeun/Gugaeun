# 안녕하세요, 구가은입니다 👋

저는 "된다"에서 멈추지 않고 "왜 되는지, 얼마나 되는지"를 확인하는 개발자입니다. 
Java·Python·JavaScript로 웹 백엔드, 프론트엔드, 안드로이드, Computer Vision까지 만들어 보며 폭을 넓혀 왔습니다.

---

## 🛠 Tech Stack

| 분야 | 기술 |
|---|---|
| **Backend** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **Mobile** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) |
| **Database** | ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) |
| **AI / Vision** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **Tools** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

---

## 🚀 Featured Project

### [Ticketing](https://github.com/Gugaeun/Ticketing) — 공연 티켓 선착순 예매 서비스
인기 공연의 티켓 오픈 순간, 동시에 몰리는 요청에도 **초과 판매나 중복 예매 없이** 처리하는 예매 서비스입니다. 동시성 문제를 일부러 재현하고, 락 방식을 바꿔 가며 **수치로 비교**하는 데 초점을 맞췄습니다.

- 재고 100장에 요청 1,000건을 동시에 보내면, 락이 없을 때 재고보다 **765~900건 더 많이 판매**됐고(H2 기준 4회 측정), 비관적 락·낙관적 락(조건부 UPDATE + 재시도)은 매번 **초과 판매 0건**
- Oracle 19c에서 k6로 HTTP 부하를 걸어 확인: 락 없음은 **실패율 0%인데도 247건이 더 팔렸고**, 두 락 방식은 0건. 속도는 방식당 1회 측정이라 우열의 결론으로 쓰지 않고 한계까지 기록
- 같은 회차 중복 예매는 DB 유니크 제약으로 막고, 예매 알림은 비동기 이벤트로 분리

`Java 17` `Spring Boot` `JPA` `Spring Security` `JWT` `Oracle` `k6`

---

## 🗂 Portfolio

프로젝트 모음 → **[Gugaeun/Portfolio](https://github.com/Gugaeun/Portfolio)**

> 🚧 일부 프로젝트는 현재도 수정·보완 중입니다.

### 👤 개인 프로젝트

| 프로젝트 | 소개 | 주요 기술 |
|---|---|---|
| [Ticketing](https://github.com/Gugaeun/Ticketing) | 선착순 티켓 예매 서비스, 락 방식별 동시성 성능 비교 | `Spring Boot` `JPA` `JWT` `Oracle` `k6` |
| [PM25](https://github.com/Gugaeun/PM25) | 서울 PM2.5 1~24시간 예측, ONNX 변환·API 서빙 | `PyTorch` `LightGBM` `ONNX` `FastAPI` |
| [mini-game-hub](https://github.com/Gugaeun/mini-game-hub) | 미니게임 10개 아케이드 사이트 · [Demo](https://gugaeun.github.io/mini-game-hub/) | `React` `Vite` `Canvas` |
| [Vision_ai](https://github.com/Gugaeun/Vision_ai) | Vision AI 실습 겸 미니 프로젝트 8종 (탐지·자세 분류·이상 탐지) | `YOLO` `Grounding DINO` `XGBoost` `PatchCore` |
| [EuroSAT-Classification](https://github.com/Gugaeun/EuroSAT-Classification) | 위성 이미지 분류, ANN·DNN·CNN × Keras·PyTorch 비교 | `Keras` `PyTorch` `CNN` |
| [golmok-hankki](https://github.com/Gugaeun/golmok-hankki) | 동네 음식점 검색·지도 서비스 (크롤링) | `Flask` `SQLite` `BeautifulSoup` `Naver Maps` |

### 👥 팀 프로젝트

| 프로젝트 | 소개 | 주요 기술 |
|---|---|---|
| [LPR_System](https://github.com/Gugaeun/LPR_System) | 번호판 인식 주차 관리 시스템 | `YOLOv11` `PaddleOCR` `PyQt6` `SQLite` |
| [Korea_Movie_Review](https://github.com/Gugaeun/Korea_Movie_Review) | 리뷰 기반 한국 영화 추천 서비스 | `FastAPI` `scikit-learn` `React` `Docker` |
| [Korean_Travel](https://github.com/Gugaeun/Korean_Travel) | 산책 코스 지도 + 기상청 날씨 여행 웹 | `JavaScript` `Kakao Maps` `Python` |
| [WithPet](https://github.com/Gugaeun/WithPet) | 반려견 동반 가능 장소 검색 앱 (입장 조건 검색) | `Android` `Java` `PHP` `MySQL` |

---

## 📚 학습 저장소

| 분야 | 저장소 | 내용 |
|---|---|---|
| 🧩 종합 실습 | [Practicum](https://github.com/Gugaeun/Practicum) | 자료구조(Python/C++), 웹 UI(배포 포함), OpenCV 기초 |
| 🐍 Python | [python](https://github.com/Gugaeun/python) | 알고리즘, 과제, 미니 프로젝트 |
| ☕ Java | [Java_2026](https://github.com/Gugaeun/Java_2026) | 기본 문법, 객체지향, 문제 풀이 |
| 🌐 Web | [Web-language](https://github.com/Gugaeun/Web-language) | HTML/CSS/JavaScript UI 구현 |
| 👁 Computer Vision | [ComputerVision](https://github.com/Gugaeun/ComputerVision) | 영상 처리 기초, YOLOv3 탐지·SORT 추적, MediaPipe, ViT, 3D 비전 |
| 🔬 Vision AI | [Vision_ai](https://github.com/Gugaeun/Vision_ai) | 객체 탐지(YOLO·Grounding DINO), 자세 분류, 이상 탐지 실습 겸 미니 프로젝트 모음 |
| 💻 C++ | [C-language](https://github.com/Gugaeun/C-language) | 기초 문법 및 자료구조 |
| 🌱 Spring *(이전 학기)* | [Java_Spring_Study](https://github.com/Gugaeun/Java_Spring_Study) | Spring 기반 백엔드 구조, REST API |
| 🗄 SQL *(이전 학기)* | [Sql_Study](https://github.com/Gugaeun/Sql_Study) | 데이터 조회 및 분석 |

---

## 📊 Language Stats

![Language Stats](https://github.com/Gugaeun/github-stats/blob/generated/languages.svg#gh-light-mode-only)

> 매일 자동으로 갱신됩니다 ([github-stats](https://github.com/Gugaeun/github-stats) Action 기반). 2021년 이전 학기 저장소(Sql_Study, Java_Spring_Study, Java_Study)는 벤더 라이브러리 코드가 많이 섞여있어 통계에서 제외했습니다.

![GitHub Stats Overview](https://github.com/Gugaeun/github-stats/blob/generated/overview.svg#gh-light-mode-only)

---

## 🎯 현재 목표

- Computer Vision 심화 학습 (YOLO 기반 객체 탐지)
- 여러 ML 프레임워크를 이해하고 상황에 맞게 선택할 수 있는 역량 키우기
- 백엔드(API 서빙)와 모델 개발을 함께 다룰 수 있는 개발자로 성장

---

## 📮 Contact

[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yms07050@gmail.com)
