# 40-2nd-FF-backend
# FF(Finding Food) README.MD

---
- 프로젝트 사이트 -> 다이닝코드
- 다이닝 코드는 빅데이터에 근거하여 소비자의 음식 코드에 맞는 음식점을 소개해주는 사이트이다.
- 위치를 기반으로 실제 이용자의 평가에 근거한 객관적인 정보를 제공한다.

# 개발 기간

---

- 2022/12/22 ~ 2023/01/06

# 실습 환경

---

Javascript
Node.js
Express.js
TypeORM

## Project Archive

---

- [Notion](https://www.notion.so/Team-F-76bf06be5d2d446990ef6e655d649cab)
- [ERD](https://dbdiagram.io/d/63a56c9899cb1f3b55a32b0b)

## 프로젝트 선정 이유

---

사용자의 현재 위치에 기반한 음식점 정보 및 평가를 전달하여, 사용자가 점심, 저녁 장소를 찾는 경험을 더욱 편리하게 하도록 하기 위함

## 주 기여

---

- OAuth : 사용자가 서비스를 편하게 이용하도록 소셜 로그인 기능 도입 및 구현 (카카오 소셜 로그인)
- OpenSource API : 사용자의 현재 위치에 기반한 정보를 제공하기 위하여 카카오 지도/로컬 API와 연동하여 현재 위치에 기반한 음식점 정보 전달 및 노출 구현
- Axios : response에 대한 효율적 처리(필요 데이터 스크리닝 및 재가공)를 위하여 fetch 대신 axios 적용 및 구현

