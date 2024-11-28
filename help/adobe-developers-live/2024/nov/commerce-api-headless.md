---
title: Headless 구현을 위한 Commerce API 오케스트레이션
description: Adobe의 소프트웨어 엔지니어인 Revanth Kumar가 API Mesh를 사용하여 향상된 보안, 성능 및 개발 간소화와 같은 이점을 통해 여러 데이터 소스를 통합하여 고성능의 Headless 상거래 경험을 관리하는 방법에 대해 알아봅니다.
solution: Commerce
feature: APIs, Headless
topic: Commerce, Development, Headless
role: Developer
level: Beginner, Intermediate
doc-type: Event
duration: 3304
last-substantial-update: 2024-11-26T00:00:00Z
jira: KT-16575
exl-id: d12d16c9-3696-48ac-9768-e87aad5191be
source-git-commit: 07d4174b0d89ba2c417866e76ae72f015b91b03a
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 0%

---

# Headless 구현을 위한 Commerce API 오케스트레이션

Adobe의 소프트웨어 엔지니어인 Revanth Kumar가 API Mesh를 사용하여 여러 소스의 API를 결합하고, 낮은 코드 환경에서 확장, 변환 및 배포하는 방법에 대해 알아봅니다. 고성능 Headless 상거래 경험을 쉽게 제공합니다.

>[!VIDEO](https://video.tv.adobe.com/v/3440402/?learn=on&enablevpops)

## 커뮤니티 토론

Adobe Developers Live 커뮤니티 [토론](https://adobe.ly/40IDxO9)에서 대화를 계속합니다.

## 주요 학습 사항

* **API Mesh 소개**
   * API Mesh는 여러 데이터 소스를 단일 GraphQL 엔드포인트로 결합하는 도구로, 프론트엔드 개발자를 위한 개발 프로세스를 간소화합니다.
   * 광범위한 GraphQL 프록시로 작동하며 향상된 보안, 제한, DDoS 보호, 낮은 코드 또는 코드 없이 비즈니스 논리를 추가할 수 있는 기능 등의 이점을 제공합니다.
* **API Mesh의 이점**
   * 여러 데이터 소스를 단일 엔드포인트로 결합하여 처리 단순화
   * 애플리케이션 성능 및 보안 향상
   * 백엔드 리소스에 대한 로드를 줄여 안정성과 견고성이 향상됩니다.
   * 배포 프로세스 속도를 높여 변경 작업을 보다 쉽고 빠르게 수행할 수 있습니다.
* **API Mesh의 기능**
   * 는 REST 끝점, GraphQL 및 JSON 스키마를 비롯한 다양한 데이터 소스를 지원합니다.
   * 필터 및 접두사 스키마를 사용하여 데이터 변환 및 충돌 관리를 허용합니다.
   * CORS 헤더 설정, 캐싱, 사용자 지정 논리 추가를 위한 후크 및 암호 관리와 같은 고급 기능을 제공합니다.
* **실제 데모**
   * 세션에는 메쉬 만들기, 소스 추가 및 배포를 포함하여 API 메쉬 설정 및 사용 방법을 보여주는 라이브 데모가 포함되었습니다.
   * 공동 개발을 위한 GitHub 코드스페이스 사용 및 메시 배포를 위한 자동화된 CI/CD 워크플로를 시연했습니다.
   * 디버깅 및 문제 해결** 중단점 설정 및 응답 검사를 포함하여 API Mesh 디버깅에 VS 코드를 사용하는 방법에 대해 설명했습니다.
   * 성능을 개선하기 위해 Fastly와 같은 CDN을 캐싱하고 사용하는 것의 중요성을 강조했습니다.
* **커뮤니티 기여 권장**
   * 사용자가 새로운 예제 또는 개선 사항으로 끌어오기 요청을 만들어 API Mesh 예제 리포지토리에 기여하도록 장려합니다.
