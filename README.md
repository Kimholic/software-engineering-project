# Random Journey Generator System

Software Engineering Project

## Description
A system that generates random travel experiences based on user preferences.

### 프로젝트 주요 기능 정의 (v1.0)
단순한 여행 플래너를 넘어 사용자에게 '예기치 못하며 우연적인 즐거움'을 주는 것을 목표로 함

1. 맞춤형 랜덤 경로 생성 엔진
 - 사용자가 입력한 예산과 기분에 맞춰서 가중치를 둔 장소를 추천
 - 무작위가 아닌 데이터 기반의 최적화된 동선을 설계하는 것이 핵심

2. 여행지 미션 시스템 (Gamification)
 - 도착한 장소에서 수행할 수 있는 간단한 미션을 부여
 - ex) "이 식당에서 가장 특이한 메뉴 사진 찍기", "로컬 주민에게 맛집 추천받기" 등 더 확장 가능

3. 실시간 지도 연동 및 시각화
 - Google Maps API를 연동해서 동선을 한눈에 파악하게 만듬
 - 단순 마커 표시가 아닌 이동 경로까지 선으로 시각화할 예정

### 개발 환경 및 도구
- 언어 및 프레임워크: JavaScript (Node.js), React
- 데이터베이스: MongoDB (사용자 성향 및 미션 데이터 관리)
- 외부 연동: 공공데이터포털(관광 데이터), Google Maps API
- 형상관리: GitHub (Issue 및 Milestone 활용 예정)
