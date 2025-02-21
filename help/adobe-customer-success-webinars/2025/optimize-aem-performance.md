---
title: AEM 성능 최적화 - 캐싱 전략 및 기법
description: 세션에서는 캐싱 전략 및 기법, 캐싱 메커니즘 및 계층, 동적 콘텐츠 처리, 디버깅 캐싱 문제 및 Dispatcher와 CDN 간의 캐시 무효화 동기화에 대해 다룹니다.
topic: Performance
role: Admin, Developer, Leader, User
level: Intermediate
doc-type: Event
duration: 3764
last-substantial-update: 2025-02-21T00:00:00Z
jira: KT-17373
source-git-commit: e7bf8b79ad4920b303fc3afbdfb4adee60614c88
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---


# AEM 성능 최적화: 캐싱 전략 및 기법

이 세션에서는 페이지, 에셋 및 Dispatcher 캐싱과 같은 다양한 캐싱 메커니즘과 CDN 수준에서 캐싱을 구현하여 콘텐츠 제공을 최적화하고 로드 시간을 줄이는 방법에 대해 살펴봅니다. 각 캐싱 계층에 대한 모범 사례, 일반적인 문제 해결 및 CDN 기능을 활용하여 효율성을 극대화하는 방법에 대해 설명합니다.

## 주요 토론 요점

* 캐싱 소개
* 캐싱 유형, 캐싱 모범 사례, 캐시 무효화 및 새로 고침
* 디버깅 기법

>[!VIDEO](https://video.tv.adobe.com/v/3444452/?learn=on&enablevpops)

## 주요 개선 사항

* **캐싱 전략 및 기법** 세션은 브라우저, CDN 및 Dispatcher와 같은 다양한 계층에서 캐싱을 포함하여 성능을 최적화하는 다양한 캐싱 전략 및 기술에 중점을 둡니다.

* **캐싱 메커니즘 및 계층** 브라우저 캐싱, CDN 캐싱 및 Dispatcher 캐싱을 포함한 다양한 캐싱 메커니즘 및 계층과 이를 구성하고 관리하는 방법에 대해 설명했습니다.

* **동적 콘텐츠 처리** 페이지에서 동적 콘텐츠를 처리하기 위한 기술에 대해 논의했습니다. 여기에는 정적 콘텐츠가 있는 동안 동적 콘텐츠가 캐시되지 않도록 하기 위해 SDI(Sling Dynamic Include) 및 ESI(Edge Side Includes) 사용이 포함됩니다.

* **캐싱 문제 디버깅** 캐싱 문제를 식별하고 해결하기 위한 헤더, 로그 및 특정 구성을 사용하는 등, 다양한 수준(브라우저, CDN, 디스패처)에서 캐싱 문제를 디버깅하는 다양한 기술에 대해 설명했습니다.

* **캐시 무효화 동기화** 세션에서는 Dispatcher와 CDN 간의 캐시 무효화 동기화 문제를 해결했습니다. 페이지 활성화 시 두 캐시가 동시에 무효화되도록 더 짧은 최대 기간 값과 CDN 제거 API를 사용할 것을 권장합니다.