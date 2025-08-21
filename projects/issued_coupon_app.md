---
layout: page
title: issued_coupon_app
permalink: /projects/issued_coupon_app/
---


# issued_coupon_app


- GitHub: https://github.com/kingofbuyeo/issued_coupon_app
- 언어: Kotlin
- Stars: 3


## 요약
Kotlin 기반의 Spring Boot WebFlux 어플리케이션으로, Redis를 활용해 쿠폰 발급 시스템을 구현한 예제입니다. 주요 기능은 쿠폰 재고 관리, 사용자별 중복 발급 방지, 그리고 Redis Stream을 통한 비동기 발급 요청 처리입니다.


## 주요 기술 스택
- Kotlin
- Spring Boot WebFlux
- Redis (Key-Value, Stream, Lua)
- Reactor


## 설치 및 실행
1. Redis 설치 및 실행:


```bash
docker-compose -f ./docker/docker-compose.yml up
