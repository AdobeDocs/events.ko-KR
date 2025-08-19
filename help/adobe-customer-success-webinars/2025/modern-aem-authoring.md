---
title: 최신 Adobe Experience Manager 작성을 위한 유니버설 편집기 개요
description: AEM의 범용 편집기 - 사용 사례, 아키텍처 간 지원 및 주요 고려 사항을 탐색하여 작성을 단순화하고 컨텐츠 전달을 활성화합니다.
solution: Experience Manager
feature: Authoring
role: Admin, Developer, User
level: Beginner, Intermediate
doc-type: Event
duration: 2891
last-substantial-update: 2025-08-19T00:00:00Z
jira: KT-18763
source-git-commit: 3b54c46988da18248024d115997704d9881f5e68
workflow-type: tm+mt
source-wordcount: '238'
ht-degree: 2%

---


# 유니버설 편집기: 최신 AEM 작성에 대한 전략적 개요

Adobe Experience Manager Universal Editor가 Edge Delivery Services에서 Headless 구현까지 다양한 아키텍처에서 콘텐츠 작성을 변환하는 방법에 대해 알아봅니다. 이 세션은 유니버설 편집기의 실제 사용 사례와 주요 기술 고려 사항에 대한 포괄적인 개요를 제공하여 프로젝트에 적합한지 여부를 확인하는 데 도움을 줍니다. AEM 환경에서 Universal Editor를 구현하는 방법에 대해 일반적인 문제를 탐색하고 정보에 입각한 결정을 내리는 방법을 알아봅니다.

## 주요 논의 사항

* 유니버설 편집기의 기본 사용 사례
* 기존 AEM Sites 컨텐츠에 대한 범용 편집기 적용 가능성
* 아키텍처 전반에 걸친 공통된 기술 고려 사항
* 자주 묻는 질문

>[!VIDEO](https://video.tv.adobe.com/v/3470850/?learn=on&enablevpops)

## 범용 편집기 기능

* **핵심 기능** 인라인 편집, 양식 기반 편집 및 모달 대화 상자를 지원합니다.
* **통합**&#x200B;은(는) 워크플로, 번역 및 다중 사이트 관리와 같은 AEM 도구와 원활하게 작동합니다.
* 사용자 지정 데이터 입력 유형, 탭 및 모달 대화 상자에 대한 **사용자 지정** 확장 지점.
* **유연성** AEM JCR, GraphQL 및 Edge Delivery 서비스를 비롯한 여러 콘텐츠 백엔드와 호환됩니다.

이러한 기능을 통해 Universal Editor는 최신 콘텐츠 관리 요구 사항을 충족할 수 있는 다양한 툴입니다.

## AEM 편집기 비교

| 기능 | AEM 페이지 편집기 | 유니버설 편집기 |
|--------------------------|-------------------------------|-----------------------------|
| **도입** | 2014(Touch UI) | 2024 |
| **콘텐츠 원본** | AEM JS | AEM JCR, GraphQL, Edge |
| **UI 프레임워크** | Coral UI | 반응 스펙트럼 |
| **사용 사례** | 기존 AEM 사이트 | 헤드리스, Edge Delivery |
| **사용자 지정** | 편집 가능한 템플릿, 스타일 시스템 | JSON 논리 스키마 |